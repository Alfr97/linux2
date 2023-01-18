FROM node:latest

WORKDIR /node-app

COPY /node-app/package.json .

RUN npm install
COPY . .
CMD [ "npm", "server.js" ]