 
 ## BUILD IN DEV MODE USING THE DOCKERFILE.DEV
 docker build -f Dockerfile.dev .
## RUN CONTAINER
 docker run -it -p 3000:3000 IMAGE_ID
 ## BUILD AND RUN  IN DEV USING DOCKER COMPOSE 
docker-compose up --build

## BUILD AND TAG IN PRODUCTION

Docker build -t [DOCKERHUBID]/[APPLICATION_NAME] .

## RUN IN PRODUCTION
We used PORT 80 due to using nginx 
docker run -p 3000:80 [DOCKERHUBID]/[APPLICATION_NAME]


