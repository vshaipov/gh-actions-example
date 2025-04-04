# Use the official NGINX image as base
FROM nginx:alpine

# Copy custom static files (HTML, etc.) into the container
# Assuming you have a "public" folder with index.html and assets
COPY public/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
