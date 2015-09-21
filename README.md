# docker-mongodump

A Docker-file to be able to dump a mongo database

## Build the image 

`sudo docker build -t ekito/mongodump`

## Run a dump

`sudo docker run --rm -v /path/to/backup:/backup ekito/mongodump -h host:port -d database -u user -p password -o /backup`