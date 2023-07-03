# Creating a Docker Image for your application

This tutorial shows you how to package an application in a Docker container image before you run that container image on a Kubernetes cluster.

# Before you begin

-	Install Docker and return to this tutorial. Docker installation varies depending on the OS you plan to use. For more information, see [Docker](https://docs.docker.com/get-docker/) docs.

For this tutorial, you will use the sample code for the application, called ExampleApp, a server written in [Python](https://www.python.org/) that responds to all requests with the message: serving at port 8000.

The application will require python dependencies to run, and you can get it from [Dockerhub](https://hub.docker.com/), a container registry, hosted by Docker.  
