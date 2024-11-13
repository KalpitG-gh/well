# Use the official Nginx image as a base
FROM nginx:alpine

# Copy the static web page files to the appropriate directory in the container
COPY ./html /usr/share/nginx/html

# Expose port 80 to serve the website
EXPOSE 80

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
