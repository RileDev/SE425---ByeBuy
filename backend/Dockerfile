FROM node:lts-alpine

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy application source code
COPY . .

# Expose backend server port
EXPOSE 5000

# Start backend application
CMD ["npm", "run", "dev"]
