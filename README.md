# devops-for-bigdata-with-cicd
Build and deploy data pipelines with cicd using modern tools and technologies.
## Docker
docker build -t image-name .
docker images
docker run image-name
docker rmi image-name:tag
dokcer rmi -f $(docker images -q)
docker ps
docker ps -all
docker run --name container-name image-name or imageid
