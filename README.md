# Docker Apps Stack Template

Start you docker server with multiple apps and reverse proxy provided by Traefik.



# Core Stack
Folder: /core/

Default Services: Portainer and Traefik

- Portainer provide you a web interface to manage your docker instance.

- Traefik provide you a reverse proxy that works with the labels of the different docker container to automatically setup ssl certificate, subdomain for your application, reverse proxy, port and url managment.



# App Stack
Folder: /apps/

Every app lives in a subfolder (example: wordpresswebsite on /apps/wpsite1/)





