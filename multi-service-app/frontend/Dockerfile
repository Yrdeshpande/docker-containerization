# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy the HTML file to the Nginx web root directory
COPY app/index.html /usr/share/nginx/html/index.html
COPY app/styles.css /usr/share/nginx/html/styles.css

# Expose port 80 to serve the content
EXPOSE 80
