# start and build compose
docker-compose up -d --build
# start and build compose
# stop compose
docker-compose stop
# stop and remove container
docker-compose down
# stop and remove container, all image
docker-compose down --rmi all

# with kafka, need to create topic before use