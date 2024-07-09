# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy the static files to the Nginx HTML directory
COPY . /usr/share/nginx/html

# Expose port 8080
EXPOSE 8080

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
