1. Запустить команду:

docker build . --tag=docker_hw_1

2. Запустить команду:

docker run -d --mount type=bind,source=$PWD/vol,target=/usr/share/nginx/html -p 6061:80 docker_hw_1
