# Use an official Node.js runtime as the base image
FROM node:alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json /app/
RUN npm install

# Copy the HTML file to the working directory
COPY index.html /app/

# Expose port 3000 (default port for 'serve')
EXPOSE 4000

# Start the app using npm start (which runs serve)
CMD ["npm", "start"]