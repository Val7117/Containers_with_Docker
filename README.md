## WARNING!
- All the credentials used in the code are only for learning & testing purposes.
- Do not put any sensistive information in the code.
- Remember to use HTTPS instead HTTP in production

## Note:
Don't forget install npm modules using **npm install** command 

## Demo Projects:
1. Use Docker for local development
2. Docker Compose - Run Multiple Docker containers
3. Dockerize Nodejs application and push to private Docker registry on AWS
4. Deploy Docker application on a server with Docker Compose
5. Persist Data with Docker Volumes
6. Create Docker repository on Nexus and push to it
7. Depoy Nexus as Docker container

===================================================
### 1. Use Docker for local development

#### **Technologies used:**
Docker, Node.js, MongoDB, MongoExpress

#### **Project Description:**
- Create Dockerfile for Nodejs application and build Docker image
- Run Nodejs application in Docker container and connect to MongoDB database container locally
- Also run MongoExpress container as a UI of the MongoDB database.

===================================================

### 2.Docker Compose - Run Multiple Docker containers

#### **Technologies used:**
Docker, MongoDB, MongoExpress

#### **Project Description:**
- Write Docker Compose file to run MongoDB and
MongoExpress containers

===================================================

### 3. Dockerize Nodejs application and push to private Docker registry

#### **Technologies used:**
Docker, Node.js, Amazon ECR

#### **Project Description:**
- Write Dockerfile to build a Docker image for a Nodejs application
- Create private Docker registry on AWS (Amazon ECR)
- Push Docker image to this private repository

===================================================

### 4. Deploy Docker application on a server with Docker Compose

#### **Technologies used:**
Docker, Amazon ECR, Node.js, MongoDB, MongoExpress

#### **Project Description:**
- Copy Docker-compose file to remote server
- Login to private Docker registry on remote server to fetch our app image
- Start our application container with MongoDB and MongoExpress services using docker compose

===================================================

### 5. Persist data with Docker Volumes

#### **Technologies used:**
Docker, Node.js, MongoDB

#### **Project Description:**
- Persist data of a MongoDB container by attaching a Docker volume to it

===================================================

### 6. Create Docker repository on Nexus and push to it

#### **Technologies used:**
Docker, Nexus, DigitalOcean, Linux

#### **Project Description:**
- Create Docker hosted repository on Nexus
- Create Docker repository role on Nexus
- Configure Nexus, DigitalOcean Droplet and Docker to be able to push to Docker repository
- Build and Push Docker image to Docker repository on Nexus

===================================================

### 7. Deploy Nexus as Docker container

#### **Technologies used:**
Docker, Nexus, DigitalOcean, Linux

#### **Project Description:**
- Create and Configure Droplet
- Set up and run Nexus as a Docker container
