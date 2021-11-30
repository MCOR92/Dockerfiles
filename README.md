# Dockerfiles
Dockerfiles
Basic repositry for Dockerfiles, so i can create images away from my local laptop. 


# Normally for most of these builds you will have to follow these instructions for building simple docker images:
mkdir Given Title
cd Given Title
vim Dockerfile
save dockerfile :wq!
build the image with the cmd: podman build -t "tagofimage:Dockerfile" .

run the command below to see the images:
podman images

REPOSITORY                                   TAG         IMAGE ID      CREATED         SIZE
localhost/secdev                             Dockerfile  a2e6ef11fb7c  17 minutes ago  714 MB
