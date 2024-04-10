# Docker Image with redhat8 base image 

This repo was created in order to test ansible roles with molecule.

## Build it locally

  docker build -t redhat8img .
  docker run --name redhat8con -d -P redhat8img
  docker exec -it redhat8con bash

## Use it from dockerhub

    https://hub.docker.com/repository/docker/lotusnoir/ansible_molecule_test_images:redhat8
