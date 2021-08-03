FROM ubuntu:20.04
FROM node:14.17.4

COPY package.json package-lock.json ./

COPY src ./

VOLUME ./src

RUN npm install

CMD ["npm", "start"]