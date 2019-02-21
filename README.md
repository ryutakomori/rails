# build and run
docker-compose up -d

# container connect
docker exec -it rails bash
docker exec -it mysql bash

# remove
docker-compose down --rmi all

# start
docker-compose start

# restart
docker-compose restart 

# stop
docker-compose stop