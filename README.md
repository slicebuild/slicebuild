Slicebuild significantly improves the processes around building Docker images.
It is not a run-time environment for deploying containers, instead it allows to easily compose Dockerfiles from the collection of predefined slices, providing a reliable and straightforward way to completely define the workflow and get the most out of application virtualization.

###How it works
Slicebuild allows packaging of predefined scripts into slices to then run them in a specific order that produces a valid Dockerfile and eventually a Docker image.   

###Standard parts
* A standalone CLI tool written in Rust for easier integration with your build processes 
* A web site for exploring and testing the best ways to build an image from slices

###Custom parts
* Define any number of slices specific to your needs
* Contribute to the community collection of slices and make your software available to anyone

###How to contribute
* By curating the slices - see slices repo: https://github.com/slicebuild/slices
* By extending the CLI tool - see the sb repo: https://github.com/slicebuild/sb
