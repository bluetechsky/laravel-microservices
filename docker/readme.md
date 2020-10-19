# Run
docker-compose -f docker/docker-compose.yml up -d --build

# Containers

Each application may require different services & configuration.
For now all applications are using the same `php:7.1-apache` image