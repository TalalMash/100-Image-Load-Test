## 100 images in a web page for internet testing
![alt text](screenshot.png)

Self-hosting alternative to http://www.http2demo.io/

HTTPS: Replace fields in Caddyfile then run `caddy run` and point your web browser to your domain name.

HTTP: `caddy file-server --listen :80 --root /path/to/your/directory`

Note: HTTP seems to be slower than HTTPS in some browsers.

## Notable tests (20 sample)

- SQM cake + layer_cake vs NONE at 60ms 100Mbit fiber: 1.3 seconds vs 0.3 seconds

- Safari vs Chrome vs Firefox: 0.5 seconds vs 0.3 seconds vs 1.6 seconds

## Credits
- Source of original photo: https://www.pexels.com/photo/beautiful-botanical-coffee-decoration-374757/

- Images cut by: https://github.com/atygaev/example-spring-boot-http1.1-vs-http2
