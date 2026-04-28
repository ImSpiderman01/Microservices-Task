FROM node:18-slim
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .

# Product Service uses port 3001
EXPOSE 3001

CMD ["node", "app.js"]