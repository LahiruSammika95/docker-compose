FROM node:13-alpine

RUN mkdir -p /home/app

COPY . /home/app

WORKDIR /home/app

RUN npm install

EXPOSE 3000

CMD ["node", "server.js"]

