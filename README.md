# docker-spcn-01 install Docker node
- [create Container Template on Proxmox](https://pve22.ipv9.me) authorited only!
- [docker install](https://docs.docker.com/engine/install/ubuntu/)
- [portainer](https://docs.portainer.io/start/install-ce/server/docker/linux)

## deploy nginx on Docker 
- `docker pull nginx`
- `docker run --name docker-nginx -p 80:80 nginx`

- `docker run --name docker-nginx -p 80:80 -d -v ~/docker-spcn-01/html:/usr/share/nginx/html nginx`
- `docker logs -f docker-nginx`

## Backup nginx config (Option)
- `docker cp docker-nginx:/etc/nginx/conf.d/default.conf default.conf`

### youtube 
- [vdo clip](https://youtu.be/gdkC9seN0mA)
