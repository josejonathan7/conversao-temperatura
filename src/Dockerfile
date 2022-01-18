FROM node:16.13.2-alpine

WORKDIR /home/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]