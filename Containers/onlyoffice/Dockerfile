# syntax=docker/dockerfile:latest
# From https://github.com/ONLYOFFICE/Docker-DocumentServer/blob/master/Dockerfile
FROM onlyoffice/documentserver:7.5.1.1

# USER root is probably used

HEALTHCHECK CMD nc -z localhost 80 || exit 1
LABEL com.centurylinklabs.watchtower.enable="false"
