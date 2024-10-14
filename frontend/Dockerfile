FROM node:lts-alpine AS builder

WORKDIR /app

COPY package*.json vite.config.js ./
RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "build"]
