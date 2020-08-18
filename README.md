# oshub.dev website
This is the open source website for 
[https://www.oshub.dev/](https://www.oshub.dev). 

## oshub
OSHub was motivated by the lack of any good repositories for virtualbox images.
There are a few available, but they don't lend themselves well to scripts that
wish to automatically obtain and deploy the image to virtualbox since they are
behind ad-walls.

This project aims to be along the lines of the services which exist for docker
containers, except it will also include virtualbox images. It will start with
a collection of base images which are vanilla OS images of fresh installs
and then expand to allowing user generated base images (in case people wish
to start from some type of additional configuration. 

Beyond the base image, I think most things can be done with docker, so I was 
thinking about some type of scripting which can specify docker containers to 
add after the base image is pulled. 

In the long run, I think it will be possible to host other artifact types on
this system, such as docker containers, pypi packages, debian packages, etc.
In this respect this project is something like an open source version of
packagecloud.

# related:
- https://www.packer.io/
