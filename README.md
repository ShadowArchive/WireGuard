# WireGuard
WireGuard Config Key Generator, made by Xin Snowflakes for Japan Servers. It was designed to be generated from the Cloudflare WARP+ Servers and created for simultaneous Projects like Home and Personal Uses, For more Information on where I am gathering my Cloudflare API Clients, Just PM me for more info.


## Use Cases:

(1): sh wan

(2): grab the results from JSON config, and example format for the config file.

`[Interface]`

`Address = 172.16.0.2/32, fd01:5ca1:ab1e:8860:45ab:e26d:6d44:3413/128`

`DNS = 8.8.8.8, 8.8.4.4, 2001:4860:4860::8888, 2001:4860:4860::8844`

`PrivateKey = IH2wEeerJpgk0B6mX0y8BSUYvTJowLeFEiwbkU5g2WA=`



`[Peer]`

`AllowedIPs = 0.0.0.0/1, 128.0.0.0/1, ::/1`

`Endpoint = engage.cloudflareclient.com:2408`

`PublicKey = bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=`

(3): save the file into wg0.conf, and import.


## Made by:

( C ) - Xin Snowflakes, 09225205353
