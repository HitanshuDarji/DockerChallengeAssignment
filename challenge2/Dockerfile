# Use the official Node.js image from Docker Hub
FROM node:14

# Copy package.json and install dependencies
COPY package*.json .
RUN npm install

# Copy the application files
COPY . .

# Expose the port the app runs on
EXPOSE 3000

# Run the app
CMD ["node", "server.js"]
