# Learning Docker!

Hi! This repository has the purpose to have all the knowledge acquired from docker through research and courses taken.
Fell free to clone this repository and learn together!


## What is Docker?
Docker is a tool for creating and managing containers. 
Container it is  a standardized unit of software, it is packages of codes and dependencies to run some code/project.

**Why use docker?** Docker it's a powerful tool since in all machines that you project will run, will always have the same behavior since the container will be the same! It's all configuration inside the container.
You don't need to worried to have in developer environment one language version (PHP8.1) in your machine and have another version in production environment (PHP7.4), with docker both environments will have the same version and extensions installed properly.

Install docker: https://docs.docker.com/engine/install/

## Commands

- Build Dockerfile: `docker build .`
- Run an image: `docker run -p {internal_port}:{docker_port} {image_id}`
- List all containers: `docker ps`
- Stop some container: `docker stop {container_name}`

## Following links
- [Docker & Kubernetes: The Practical Guide [2023 Edition]](https://www.udemy.com/course/docker-kubernetes-the-practical-guide)



Written with [StackEdit](https://stackedit.io/).