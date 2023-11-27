
# Run following command on terminal

docker build -t 101356047_hello_docker .

docker image ls

docker run -p 4000:80 101356047_hello_docker

docker run -d --name=lab11-devops -p 4000:80 101356047_hello_docker

docker container stop CONTAINER_ID

docker container ls