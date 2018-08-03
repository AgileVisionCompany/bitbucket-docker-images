FROM openjdk:8-jdk

MAINTAINER AgileVision.io "https://agilevision.io"

RUN apt-get update
RUN apt-get install -y chromium python-dev build-essential
RUN curl -O https://bootstrap.pypa.io/get-pip.py
RUN python get-pip.py
RUN pip install awscli
RUN pip install awsebcli --upgrade 

