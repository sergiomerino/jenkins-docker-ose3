# jenkins-docker-ose3
Demo to show how to integrate jenkins with ose3

## Procedure (step by step)
First of all, we need to instance a docker container with jenkins.

'docker run -d --name jenkins-test -p 50000:50000 -p 8080:8080 -v /var/jenkins_home:/var/jenkins_home jenkins'

but we need to install plugins and something like this and it´s neccessary to connect this container with the proxy. So, we need to modify
the image jenkins:latest in order to pass HTTPS_PROXY and HTTP_PROXY values.







