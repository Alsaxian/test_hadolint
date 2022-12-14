# Start from the latest Ubuntu image
FROM ubuntu:latest

# Install the nginx package from apt
RUN apt-get update && apt-get install -y nginx

# Copy the nginx configuration file to the correct location
COPY nginx.conf /etc/nginx/nginx.conf

# Expose the default nginx port (80)
EXPOSE 800000

# Run the nginx command when the image is run
CMD ["nginx", "-g", "daemon off;"]