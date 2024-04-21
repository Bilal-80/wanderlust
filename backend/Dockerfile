FROM node:21
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm i
COPY . .
COPY .env.docker .env
EXPOSE 5000
CMD ["node","server.js"]
