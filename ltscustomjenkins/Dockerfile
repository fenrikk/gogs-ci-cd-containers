FROM jenkins/jenkins:lts-jdk17
USER root
RUN apt update && curl -fsSL https://get.docker.com/ | sh
RUN usermod -aG docker jenkins
RUN newgrp docker
USER jenkins