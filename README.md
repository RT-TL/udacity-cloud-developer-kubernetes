# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Prerequisitives
0. Install docker https://docs.docker.com/install/.

## Update images manually
0. Navigate to /udacity-c3-deployment/docker/, open a new terminal
1. Build the images: `docker-compose -f docker-compose-build.yaml build --parallel`
2. Push the images: `docker-compose -f docker-compose-build.yaml push`

## Running locally
0. Navigate to /udacity-c3-deployment/docker/, open a new terminal
1. Run the container: `docker-compose up`

