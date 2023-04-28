FROM node:12-alpine

WORKDIR /app

COPY . /app

ENV PORT 80

EXPOSE 80

RUN npm install 

CMD [ "node", "server.js"]
