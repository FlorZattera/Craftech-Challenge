FROM node:16-alpine

EXPOSE 3000
WORKDIR /app

COPY package*.json /app

RUN npm i

COPY . /app
CMD ["npm", "run", "start"]
