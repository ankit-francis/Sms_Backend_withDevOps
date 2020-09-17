FROM node:latest

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN npm install --only=poduction

CMD ["node","server.js"]

EXPOSE 4000

