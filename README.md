# container-and-kube
Container and Kube demo

Before:
git clone <uri>
cd <filename>

Commands to build and run docker image locally
docker build -t kube-service .
docker run -p 8080:8080 kube-service
To list all images
docker images
To find current running docker process
docker ps -a
To stop a container
docker stop
To remove an image
docker rmi
To go inside the container
docker exec -it <image-id> /bin/sh
  
  
