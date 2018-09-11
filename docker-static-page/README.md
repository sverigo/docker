Deploy Static HTML Website as Container with Docker


MANUAL:

1. Build Docker image from Dockerfile:
  $ docker build -t static-webserver-image:v1 .

2. Run Docker image
  $ docker run -d -p 80:80 static-webserver-image:v1


Now the page is available at http://localhost:80
