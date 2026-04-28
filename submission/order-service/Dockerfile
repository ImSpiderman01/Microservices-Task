FROM node:18-slim
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .

# Order Service uses port 3002
EXPOSE 3002

CMD ["node", "app.js"]