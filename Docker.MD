# Docker

#### What is the problem statement?

Assume you created a software which has a particular set of dependencies here and it will work the same versions.

#### Why Docker was needed?
#### What is Docker?

A new team member has joined you there and want to work on the same project but the system may be different than yours. To match the required version and same dependencies. We have a tool to handle that problem, which is solved by `Docker`.

In software development, many developers will work on the same project, so you can't say that the project works on your system, that why it will be used. It must run for others also.

## Docker Container

What is Docker Container?

A container which contains app and its dependencies which help the to function properly over a system.

Thus containers are the standardised way to share the application with required dependencies or basically replicating the entire system in a standard way across a large team.

### Properties of a Container:
1. Portable
2. Lightweight in nature
3. Helps in maintaining the version

## Docker Image
What is Docker Image?

It is an executable file of docker container. 
It contains instructions to build containers.
It is like the relation between class and object. 
As we can make different objects through a single class.
Similarly, we can make multiple containers through a single image.

Thus, when we want to share application with its dependencies, we share the  docker image, not the docker container.

As objects of class has their own properties and details. So, as well they use the system resources to store them. Similarly,our system resources are used by the containers not the images.

Thus, the size of the image is lesser than the container.

In the container, the running environment is setup due to which it uses the system resources.

A docker container is a running instance, where as a docker image is a static snapshot or static screenshot of a local development environment should look like.



```bash
docker # to see all the commands

docker -v # to check the version of docker

docker pull image_name # to pull an image from docker hub

docker images # it will list all the images installed here

# or you can also use the below command to list all the images

docker image ls # it will list all installed images of the system

docker run image_name # it will create a new container with the image to asked for

docker run -it ubuntu 
# -it means to run the ubuntu vm in interactive mode
```

