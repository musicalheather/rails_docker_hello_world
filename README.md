# README

This is a basic Rails Hello World application that is containerized with Docker. When run, it displays "Hello World!"

I included a gitlab-ci.yaml file showing the pipeline where it deploys a postgres database first and then installs the rails application. It tests the install and then pushes and runs the docker file. In the past I've pushed the docker image to ecr and then used kubectl to update production, but that's beyond the scope of this project. 