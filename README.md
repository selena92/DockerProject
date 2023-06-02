# DockerProject

Run the following commands to build your Docker image:

$ docker build -t my-apache2 .

$ docker run -dit --name my-running-app -p 8080:80 my-apache2
