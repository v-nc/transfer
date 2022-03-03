FROM node:lts-buster
WORKDIR /usr/src/app
COPY . /usr/src/app
RUN npm install
RUN npm update node-opcua 
RUN apt-get update
RUN apt-get install nano
