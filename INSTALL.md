# Install Instructions

This project pushes the images to my docker-hub repository. If you want to modify the Dockerfile and push them to your own registry and repository you are welcome to. I'd love to get any feedback on improvements.

## Building

Building is simple using [docker-build](https://github.com/bintzpress/docker-build). 

1. Copy .env_sample to .env and edit as needed.
2. Run the docker-build command. This will read in the docker-build-set.yml which tells where the other docker-build.yml files are.