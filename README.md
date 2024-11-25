# nodejs-docker-aws-ecs

AWS Project - CI CD Pipeline to AWS ECS for Docker App + CodeCommit + CodeBuild + CodeDeploy

## Installation

Follow next steps in order to install nodejs app and create a dockerimage

### Build and run docker container

```
docker build -t nodejs-server-demo .
```

```
docker run -dp 3000:3000 nodejs-server-demo
```