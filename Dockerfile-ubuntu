# Image
FROM ubuntu:22.04

# New project
USER root

#COPY  . . opção para copiar tudo
RUN apt-get update && apt-get install nginx -y
RUN apt-get -y install wget curl vim net-tools
RUN apt-get -y install vim nano tree

COPY requirements.txt requirements.txt

RUN pip install --no-cache -r /requirements.txt