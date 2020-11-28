# specifies node version number, 14
FROM node:14

WORKDIR /app

COPY . /app

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]