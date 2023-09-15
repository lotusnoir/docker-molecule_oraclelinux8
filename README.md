# Docker Image with oraclelinux8 base image 

This repo was created in order to test ansible roles with molecule.

## Build it locally

  docker build -t oraclelinux8img .
  docker run --name oraclelinux8con -d -P oraclelinux8img
  docker exec -it oraclelinux8con bash

## Use it from dockerhub

    https://hub.docker.com/repository/docker/lotusnoir/ansible_molecule_test_images:oraclelinux8
