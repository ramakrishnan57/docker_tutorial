# docker_tutorial


git clone git@github.com:geshan/nginx-docker-compose.git


version: '3.8'
services:
  nginx:
    image: nginx:1-alpine
    ports:
      - 8089:80
    volumes:
      - ./html5up-stellar/:/usr/share/nginx/html


      docker compose -f basic.yaml up
