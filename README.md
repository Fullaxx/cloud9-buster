# A Cloud9 docker image based on Debian 10 (Buster)

## Base Docker Image
Debian 10

## Get the image

Download an automated build from the public Docker Hub Registry:

    docker pull fullaxx/cloud9-buster

## Usage

    docker run -d -p 80:80 fullaxx/cloud9-buster

You can add a workspace as a volume directory with the argument *-v /your-path/c9ws/:/c9ws/* like this :

    docker run -d -p 80:80 -v /your-path/c9ws/:/c9ws/ fullaxx/cloud9-buster

## Build it locally using the Dockerfile on github

    docker build -t="fullaxx/cloud9-buster" github.com/Fullaxx/cloud9-buster
