To run any example, you need to build a docker image, and then run the container:
 
 docker build -t <image-name> <files (. - all files in directory)>
 docker run -d --name <container-name> -p <port>:<port> <image-name>
