# gdmt-deployment-config

This repository contains the configuration files for the deployment of the GDMT project.

Commands to deploy infrastructure applications:

docker-compose -f docker-compose.networks.yaml -f gdmt-ms-vault-server/docker-compose.yaml -f gdmt-ms-postgres-server/docker-compose.yaml -f gdmt-ms-eureka-server/docker-compose.yaml -f gdmt-ms-config-server/docker-compose.yaml -f gdmt-ms-oauth2-server/docker-compose.yaml -f gdmt-ms-zuul-server/docker-compose.yaml -p gdmt-infrastructure-apps up -d