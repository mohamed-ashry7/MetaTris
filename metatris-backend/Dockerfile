
FROM node:17

RUN mkdir -p /app

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD [ "npm", "start" ]
