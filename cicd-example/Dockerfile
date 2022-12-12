FROM node:14-alpine

WORKDIR /app
COPY . /app

RUN npm install
RUN npm run build:docker

CMD [ "npm","run","start:prod" ]
