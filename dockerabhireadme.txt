# To build docker image run: docker-compose build

# To run docker container run: docker-compose up

# To stop docker container run: docker-compose down

# Rebuilding Docker Services

# To rebuild docker image run: docker-compose build

# to migrate run :  docker-compose run web python manage.py migrate


based on this youtube video: https://youtu.be/fC4OF9uDhCo


Restart and Rebuild

docker-compose down --volumes
docker-compose up --build
