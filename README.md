# challenge-docker

## What

We try to understand docker trough this exercise. It is our first exercise on Docker.

## Why

To be able to understand and work with Docker. To be able to understand what is an image, how it works and how to change it when it is running.

## When

During BeCode training, we start on 22 December 2020 and finished on 23 December 2020.

## How

First, you have to install Docker's application on your computer. You can found it [here](https://www.docker.com/)
Then you can clone this repesitory with:

`git clone https://github.com/EbubekirKocadag/challenge-docker.git`

In this project, you have a Dockerfile which is creating an image to do that you have to run in terminal `docker build . -t 'nameofyourimage'`.
This will create the following structure:

/app
    |-docker
    |   |-Dockerfile -> your Dockerfile
    |-pipeline
    |   |
    |   |-model
    |   |    |-model.py -> print a number between 1 and 400
    |   |-preprocessing
    |   |    |-preprocessing.py -> print a numpy array
    |   |-utils
    |   |    |-utils.py -> print "in progress..."
    
Once you have created your image, you can run it with `docker run -t nameofyourimage`. If you want to run the bash you only need to add `:latest bash`
after the previous code.

You can also change everythin of a running container with volume and to do it you have to run 
`docker run -v 'path of your repository':'path in your image' -t 'nameofyourimage` in your terminal.
And then you can change whatever you want. It will change on your computer too.

## Who

[Ebubekir Kocadag](https://github.com/EbubekirKocadag), junior AI developer
