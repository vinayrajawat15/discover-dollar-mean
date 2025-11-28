# Use Node LTS
FROM node:18

# Create working directory
WORKDIR /app

# Copy package.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy rest of backend code
COPY . .

# Expose backend port
EXPOSE 8080

# Start backend
CMD ["node", "server.js"]
