FROM node:16.18.0-alpine

WORKDIR /chat-server

COPY package*.json .

RUN npm install

COPY . .

RUN npm run config

EXPOSE 6060

CMD ["npm", "start"]
