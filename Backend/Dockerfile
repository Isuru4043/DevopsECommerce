#Docker file 

FROM node:22

RUN npm install -g nodemon

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 8000

CMD ["node", "server.js"]