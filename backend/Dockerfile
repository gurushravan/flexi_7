# Use an official Node.js image
FROM node:14-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the application code
COPY . .

# Expose the backend port
EXPOSE 5000

# Start the backend service
CMD ["node", "server.js"]
