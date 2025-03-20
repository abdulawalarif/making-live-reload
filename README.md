1. Command for building the image:


`docker build -t my-go-docker .`


2. command for running the container:


`docker run -p 8080:8080 --rm -v $(pwd):/app -v /app/tmp --name my-go-docker-air my-go-docker`