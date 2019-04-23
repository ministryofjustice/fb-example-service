# fb-example-service

Form Builder example service

## Pre-requisites

  [Docker](https://www.docker.com/products/docker-desktop)

## Installing

```
git clone git@github.com:ministryofjustice/fb-example-service.git

git clone git@github.com:ministryofjustice/fb-runner-node.git
cd fb-runner-node
docker build -t fb-runner-node .
```

## Usage

```
cd fb-runner-node

docker run -it -p <LOCAL_PORT_NUMBER>:3000 --rm -v <PATH_TO>/fb-example-service:/usr/src/fb-service -e SERVICE_PATH="/usr/src/fb-service" fb-runner-node
```
