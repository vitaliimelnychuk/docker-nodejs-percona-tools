# docker-nodejs-percona-tools
Contains Dockerfile instructions that helps to use migrate mysql databases.

It's like initial repository that helps when you want to create your own migration database repository and would like to use nodejs as version manager and percona-tools as migration tool without downtimes


## docker build

docker build . -t nodejs-percona-tools

## docker run 

docker run -v $(pwd):/code --rm nodejs-percona-tools
