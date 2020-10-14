# ECE444-F2020-Lab4
Author: Beiqi Li

This repo is a clone of
https://github.com/miguelgrinberg/flasky

## To build the project:

Run the following command to build the docker image:

```
docker build -t [image_name]:[version_number] .
```

The Dockerfile is located at root directory.

## To run the project:
Run the following command to start the docker container:

```
docker run --it --rm --name [container_name] -p 5000:5000 [image_name]
```

## Snapshots

### Docker run command

![docker_run](https://github.com/libeiqibns/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/docker_run.png)

### Docker image

![docker_image](https://github.com/libeiqibns/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/docker_image.png)

### Website

![website](https://github.com/libeiqibns/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/website.png)

## Difference between Docker container and Virtual Machine

Docker containers share the same OS kernel. Virtual Machines do not. Therefore, Virtual Machines consume more resources and have longer startup time. However, since Virtual Machines do not share the OS kernel, VMs provide better isolation. This is considered as a security advantage.
