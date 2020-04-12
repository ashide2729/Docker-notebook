# Docker-notebook
This repository is contains notebook on docker and it's related concepts. The notebook is tailored in such a way that it helps anyone to understand the concept of docker and how to get started with docker. The content is doesn't contain long lengthy pages it contains brief but easy to understand each and every concept mentioned so that in short time one can brush up their docker concept and at the same time learn to get started with it.

## Docker:

Docker is a platform that provides software delivery in packages called containers.
Now before we dive into Docker first we should know what is a Container and what is an Image.
Docker deals in images and running containers.

## Images: 

A docker image is a file that executes code in a container.

## Container:

It is the running instance of an image.
There are images of applications like Ubuntu, Postgres etc. on Docker Hub which run in a container.
Images can be fetched from Docker Hub and can also be created from pre-existing ones.

## Why Docker?

Suppose we want to run an application on a different machine and for that application to run in that machine we need Angular, Node, MongoDB so in order to deliver that software with all other applications to run successfully we create a container using images of all these files running inside it. Once we have this container running we can create a new image with all these other images inside and deliver the whole package for later to use which was not possible earlier.
Docker can be run using the terminal once installed. Docker provides commands to perform operations.

## Docker use case:

Suppose we created a web application on our local system(laptop or PC) and now want that application to run on the WWW. But to achieve this we need to bundle the whole application with other minimum requirements like other applications needed to run it which were present on our system but are not present on the server machine where we deploy the application. 
That is where Docker comes in which helps us bundle the application with all the other requirements and send it across for usage with no application failure due to missing requirements.

## Docker How to?

Now to Dockerize our application let’s take the basic procedure:
1.)	Install Docker on your system 
2.)	Using “docker pull” pull the required images like ubuntu, mongoDB, Angular etc.
3.)	Run the image of ubuntu which will run as container
4.)	Run other images inside it too
5.)	Once that is achieved create an image of it and do “docker push” that will result in final image
