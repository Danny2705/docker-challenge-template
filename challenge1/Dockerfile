# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the public folder content to Nginx's html folder
COPY public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
