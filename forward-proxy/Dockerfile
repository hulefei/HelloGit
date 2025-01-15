# Use the official Nginx image as a base
# FROM csighub.tencentyun.com/hlibrary/nginx:latest
FROM nginx:latest

# Copy the custom Nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Expose the port that Nginx will listen on
EXPOSE 8080

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
