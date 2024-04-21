FROM node:21
WORKDIR /app
COPY . .
RUN npm i
COPY .env.docker .env
EXPOSE 5173
CMD ["npm","run","dev","--","--host"]
