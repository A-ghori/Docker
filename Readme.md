# What is Docker -> 
## Docker is a platform designed to help developers build, share, and run container applications. An analogy of Maggi noodles explains Docker as a tool that bundles software and its dependencies into a portable container to ensure it runs consistently anywhere 


## Why Do We Nedd Dockers

- # Consitency Across Enviroment

- ## Problem : Application often behave differently in development, testing, and production enviroments due to variations in configurations, dependencies , and infrastructure

- ## Solution : Docker containers encapsulate all the necessary components, ensuring the applications runs consistently across all enviroments



- # Isolation 

- ## Problem : Running multiple applications on the same host can lead to conflicts , such as dependency clashes or resource contention

- ## Solution : Docker provides isolated enviroments for each applications, preventing interference and ensuring stable permance 


## Docker Engine : The core component responsible for managing containers.
## Docker Image : A static snapshot or template of the application.
## Docker Container : An executable, running instance of an image.
## DockerFile : A text file containing instructions to build an image.
## Registry : A service (like Docker Hub) to store and distribute images.


# The distinction between a Docker image and a container is foundational to how Docker works:

## Docker Image : Think of this as a static snapshot or a template. It is a read-only file that contains the source code, libraries, dependencies, and configuration files required to run an application. It is the "recipe" or "blueprint" for your software.

## Docker Container : This is the executable, running instance of an image. When you run an image, you create a container—an isolated, lightweight environment where your application actually executes. While an image is the file on your disk, the container is the live process running on your system.

## In short, you build an image and then you run it as a container


