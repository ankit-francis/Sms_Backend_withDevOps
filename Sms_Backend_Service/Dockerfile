FROM node:latest

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN cd /SMS_BACKEND_WITHDEVOPS/Sms_Backend_Service

RUN npm install --only=poduction

CMD ["node","server.js"]

EXPOSE 8080

