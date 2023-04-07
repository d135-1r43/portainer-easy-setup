# portainer-easy-setup

A simple docker-compose.yaml to start a minimal and persistent single host portainer. 

It starts `portainer-ce`, makes the docker.sock available while persisting it's data locally to `/opt/portainer`. It also creates a network called `nginx-proxy-manager` for further usage with [NGINX Proxy Manager](https://nginxproxymanager.com). 
