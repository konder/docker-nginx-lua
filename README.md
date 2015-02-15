NGINX with lua, cjson
---

# RUN

```shell
docker run --name nginx -p 80:80 -p 443:443 -d -v /PATH-TO-SHARE:/share -v /PATH-TO-CONFIG/nginx.conf:/etc/nginx/nginx.conf konder/nginx-lua
```
