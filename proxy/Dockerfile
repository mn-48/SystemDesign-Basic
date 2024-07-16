# Use the official NGINX image from the Docker Hub
FROM nginx:alpine

# Copy the custom nginx.conf to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 8081
EXPOSE 8081

# Start NGINX server
CMD ["nginx", "-g", "daemon off;"]
