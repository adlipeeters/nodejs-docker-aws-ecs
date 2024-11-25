# nodejs-docker-aws-ecs

AWS Project - CI CD Pipeline to AWS ECS for Docker App + CodeCommit + CodeBuild + CodeDeploy

## Installation

Follow next steps in order to install nodejs app and create a dockerimage

### Step 1 - Git clone 

```
git clone https://github.com/saasscaleup/nodejs-ssl-server.git
```

```
cd nodejs-ssl-server
```

```
git checkout nodejs-docker-aws-ecs
```

### Step 2 - Build and run docker container

```
docker build -t nodejs-server-demo .
```

```
docker run -dp 3000:3000 nodejs-server-demo
```