FROM node:alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 4040
CMD [ "npm", "run", "start:prod" ]
