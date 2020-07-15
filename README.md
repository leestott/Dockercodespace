# Docker To Visual Studio Codespace

In this demo we are using a custom DockerHub Image for deployment to Visual Studio Codespace

## Key requirements ## 

1. A custom dockerhub image created 
2. Image is uploaded to Dockerhub in the case of this example
3. Notebook folder contains a sample jupyter notebook
4. Data includes a sample data set 

Simply deploy at Visual Studio Codespaces

# Running the container in Visual Studio Online (Browser Experience)

## One Button Click Deploy

[![Open in Visual Studio Online](https://img.shields.io/endpoint?style=social&url=https%3A%2F%2Faka.ms%2Fvso-badge)](https://online.visualstudio.com/environments/new?name=Dockerdemo&repo=leestott/Dockercodespace)

The way this works is as follows is simply calling a specific URL which creates your Visual Studio Online Environment

https://online.visualstudio.com/environments/new?name=Dockerdemo&repo=leestott/Dockercodespace

We also have the domain env.new which allows you to replace online.visualstudio.com making the url shorter

https://env.new?name=Dockerdemo&repo=leestott/Dockercodespace

You could also load this in a new window using target="_blank" so as an example so <a href="https://new.env?name=..." target="_blank">{your image}</a>
