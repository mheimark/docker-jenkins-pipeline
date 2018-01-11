# docker-jenkins-pipeline
A project making use of Jenkins pipeline running inside docker container, managed from gradle plugin

Use gradle plugin to interact with docker-cli and run containers on startup
Run git repo in docker image
Push to repo
Jenkins picks up Jenkinsfile (pipeline). (Jenkins running in container)
Jenkins builds and runs part of its build inside container
Jenkins publishes and deploys the microservice
