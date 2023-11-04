FROM node:latest
RUN apt-get update
RUN apt-get install git
RUN git clone https://github.com/jishi/node-sonos-http-api.git
WORKDIR node-sonos-http-api
RUN npm install --production
CMD ["npm", "start"]