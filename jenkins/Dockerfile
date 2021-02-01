ARG JENKINS_VERSION

FROM jenkins/jenkins:${JENKINS_VERSION}

USER root

RUN apt-get update

RUN apt-get install -y maven sudo
