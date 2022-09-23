# simple-download-server-nginx

fonte:
https://www.pluralsight.com/guides/download-large-files-from-remote-servers-using-nginx-docker

## To start the container for the first time:
docker-compose up -d

## To start the container repeatedly:
docker-compose start

## To stop the container:
docker-compose stop

## To restart the container:
docker-compose restart

## To stop the container and remove the images from your host machine:
docker-compose down

## Teste
curl localhost:8080/arquivos/teste.txt
