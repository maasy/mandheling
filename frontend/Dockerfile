FROM node:15.14-alpine

WORKDIR /app

RUN apk update
COPY package.json .
RUN npm install