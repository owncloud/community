This folder includes resources and information on the workshop: <br/>
**Install and Deploy ownCloud File Sync and Share with Collabora Online Open Source Document editing to be in complete control of your data** <br/>
Saturday August 15th 2026<br/>
15:15–17:15, Workshop (C115)<br/>
https://programm.froscon.org/froscon2026/talk/aa8d9417-4867-4e3b-8e71-0d2bef9d3bc5/

## Relevant Links:
### Community:
- https://owncloud.dev/join
- https://owncloud.com/events


This workshop was created using the ownCloud Admin docs:
- Local (part 1)
  https://doc.owncloud.com/ocis/latest/admin/depl-examples/ubuntu-compose/ubuntu-compose-prod.html
- Deployment (part 2)
  https://doc.owncloud.com/ocis/latest/admin/depl-examples/ubuntu-compose/ubuntu-compose-hetzner.


## Downloads:
- Docker: https://www.docker.com/products/docker-desktop/
- Docker Compose & Configuration files:<br/>
  https://download-directory.github.io/?url=https://github.com/owncloud/ocis/tree/master/deployments/examples/ocis_full

## Slides
*Will be added after the workshop is completed and we've updated the information based on participant feedback* 

## Cheat sheets:
### Internal & Testing links:
- ocis.127-0-0-1.sslip.io
- collabora.127-0-0-1.sslip.io

### ENV edits:
INSECURE=true <br/>
OCIS_DOMAIN=ocis.127-0-0-1.sslip.io <br/>
OCIS_DOCKER_TAG=8.2 *//set tis explicitly as you have better control on which version you are downloading*  <br/>
ADMIN_PASSWORD=froscon2026  <br/>
DEMO_USERS=true <br/>
#TIKA=:tika.yml *//uncomment for local*  <br/>
COLLABORA_DOMAIN=collabora.127-0-0-1.sslip.io <br/>
COLLABORA_ADMIN_USER=admin <br/>
COLLABORA_ADMIN_PASSWORD=froscon2026  <br/>
 <br/>
//WINDOWS USERS: <br/>
COMPOSE_PATH_SEPARATOR <br/>

### Commands:
docker compose pull <br/>
docker compose up -d <br/>
docker compose down <br/>


