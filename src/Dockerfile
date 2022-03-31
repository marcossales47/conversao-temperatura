FROM node:latest
WORKDIR /app
COPY package*.json ./
RUN npm install -y
EXPOSE 8080
COPY . .
CMD ["node", "server.js"]

