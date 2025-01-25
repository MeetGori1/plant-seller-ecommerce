# Dockerfile for Backend
FROM node:18-alpine

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

# Start the server
CMD ["npm", "start"]

EXPOSE 5000
