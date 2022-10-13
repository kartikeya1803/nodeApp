FROM node:14-slim

WORKDIR /app/listings

COPY package*.json ./


RUN  npm install --omit=dev


COPY . .

EXPOSE 3000

CMD [ "npm","start" ]
