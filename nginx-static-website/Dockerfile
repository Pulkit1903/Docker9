# Use the official Nginx image as the base image
FROM nginx:latest

# Copy your static web page files into the Nginx default directory
COPY ./static-html /usr/share/nginx/html

# Expose port 80 for web traffic
EXPOSE 80

# Start the Nginx web server when the container runs
CMD ["nginx", "-g", "daemon off;"]

