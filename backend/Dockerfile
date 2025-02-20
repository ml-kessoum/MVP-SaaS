FROM node:20

RUN mkdir -p /app

WORKDIR /app

COPY package*.json /app

RUN npm install -g @nestjs/cli@11
RUN npm install

COPY . /app

EXPOSE 4000
EXPOSE 4100