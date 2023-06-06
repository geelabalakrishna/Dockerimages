# Use a base image
FROM nginx:alpine

# Copy the contents of the dist directory into the container
COPY dist /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start the Nginx web server
CMD ["nginx", "-g", "daemon off;"]
