# DockedAngular
practice app to create a dockerised angular application


# Docker Commands

1. docker build -t angular-front .
2. docker run -d -p 4200:4200 angular-front

## Or 

1. docker build . -t my-web-app -f Dockerfile.old
2. docker run -d -p 80:80 my-web-app  


## Service API Commands