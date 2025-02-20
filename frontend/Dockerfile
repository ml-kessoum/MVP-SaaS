FROM node:20-slim

RUN mkdir -p /app
WORKDIR /app

COPY package*.json ./

RUN npm install -g @angular/cli@19

RUN npm install

COPY . .

EXPOSE 4200
