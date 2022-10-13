FROM node:14-slim

WORKDIR /server

COPY package*.json ./

RUN npm install --omit=dev

COPY . .

EXPOSE 5000

CMD [ "npm","start" ]
