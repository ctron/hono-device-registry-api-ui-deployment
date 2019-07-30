# Deployment of Eclipse Hono™ Device Registry API UI

This repository contains the deployment for the Swagger UI of the Eclipse Hono
device registry API.

The API can be explored at: https://v1-hono-device-registry-api.apps.wonderful.iot-playground.org/

## Deployment

First, create a new project:

    oc new-project hono-device-registry-api

The deploy the YAML files:

    oc apply -f deploy/
