# docker-r-studio

## Description

To allow usage of R-Studio in a portable way using a Docker Container

## Procedure
### Build the image

` docker login` - to authenticate
` docker build -t adam-d-mckinnnon/docker-r-studio .`

### Run Container

`docker run --rm -p8787:8787 -e USER=myself -e PASSWORD=guest -v /Users/adammckinnon/R_Studio_Shared:/home/myself/r-studio adam-d-mckinnon/docker-r-studio
