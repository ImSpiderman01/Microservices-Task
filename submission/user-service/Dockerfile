FROM node:18-slim

WORKDIR /usr/src/app

# Copy dependency files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# User Service uses port 3000
EXPOSE 3000

CMD ["node", "app.js"]