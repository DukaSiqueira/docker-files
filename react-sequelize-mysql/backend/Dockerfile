FROM node:latest

WORKDIR /app/backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npx", "nodemon", "index.js"]