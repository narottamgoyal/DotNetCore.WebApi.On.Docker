# DotNetCore.WebApi.On.Docker

Run the below command to deploy sample dotnet web api code on docker

        docker-compose build
        docker-compose up

# Docker basic command

- Docker machine ip (If running using Docker Toolbox)

        docker-machine ip  (this will print 192.168.99.100)

- View all docker image

        docker images

- Delete docker image

        docker rmi -f imageId_1 imageId_2..  (-f = force)

- View all running container

        docker ps -a  (-a = include exited container)

- Delete container

        docker rm containerId
        docker container prune (this remove all exited containers)

- Run container

         docker run -d -p 8086:80 imageId (-d = run in background, browse the app using 8086 port)

- Docker help Command

        docker --help

- Generate Docker file from Visual studio

  ![image](https://user-images.githubusercontent.com/2716202/78424475-6367bb00-765d-11ea-868e-9c23400ea08b.png)

