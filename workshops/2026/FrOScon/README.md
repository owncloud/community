This folder includes resources and information on 
"Install and Deploy ownCloud File Sync and Share with Collabora Online Open Source Document editing to be in complete control of your data"
Saturday August 15th 2026
15.08.2026 15:15–17:15, Workshop (C115)
https://programm.froscon.org/froscon2026/talk/aa8d9417-4867-4e3b-8e71-0d2bef9d3bc5/

## Relevant Links:
### Community:
- owncloud.dev/join
- owncloud.com/events


This workshop was created using the ownCloud Admin docs:
- Local (part 1)
  https://doc.owncloud.com/ocis/latest/admin/depl-examples/ubuntu-compose/ubuntu-compose-prod.html
- Deployment (part 2)
  https://doc.owncloud.com/ocis/latest/admin/depl-examples/ubuntu-compose/ubuntu-compose-hetzner.


## Downloads:
- Docker
- Docker Compose & Configuration files - 
  https://download-directory.github.io/?url= https://github.com/owncloud/ocis/tree/master/deployments/examples/ocis_full

## Slides 

## Cheat sheets:
### Internal & Testing links:
ocis.127-0-0-1.sslip.io
collabora.127-0-0-1.sslip.io

### ENV edits:
INSECURE=true
TRAEFIK_ACME_MAIL=you@example.com   //not required for local only
OCIS_DOMAIN=ocis.127-0-0-1.sslip.ioOCIS_DOCKER_TAG=8.2 //set tis explicitly as you have better control on which version you are downloading
ADMIN_PASSWORD=froscon2026
DEMO_USERS=true#TIKA=:tika.yml    //uncomment for local
COLLABORA_DOMAIN=collabora.127-0-0-1.sslip.io
COLLABORA_ADMIN_USER=admin
COLLABORA_ADMIN_PASSWORD=froscon2026
//WINDOWS USERS: COMPOSE_PATH_SEPARATOR

### Commands:
docker compose pull
docker compose up -d
docker compose down


