# Use the official NGINX image as the base image
FROM nginx:alpine

# Copy the HTML file into the NGINX web directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to allow access to the web server
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]