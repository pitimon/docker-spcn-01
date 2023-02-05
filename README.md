# docker-spcn-01
 
- `docker pull nginx`
- `docker run --name docker-nginx -p 80:80 nginx`

- `docker run --name docker-nginx -p 80:80 -d -v ~/docker-spcn-01/html:/usr/share/nginx/html nginx`
- `docker logs -f docker-nginx`

# Backup nginx config (Option)
- `docker cp docker-nginx:/etc/nginx/conf.d/default.conf default.conf`