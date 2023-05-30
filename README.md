This repo ncludes all files necessary to deploy my modified Tandoor version. 

The docker image is available at: https://hub.docker.com/repository/docker/annananx/tandoor_modified.
Pull the image as well as the docker-compose.yml and .env file. 
To start the container run "docker compose up" in the directory of the files.

Changes to the original Tandoor app include: 
* making the navbar static
* reworking the copy to clipboard functionality (in the shopping bar tab) to paste plain text
* cleaning up the recipe view to be more compact
