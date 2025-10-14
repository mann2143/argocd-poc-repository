# Use official Nginx base image
FROM nginx:latest

# Expose default Nginx port
EXPOSE 80

# Start Nginx in foreground (so container doesn't exit)
CMD ["nginx", "-g", "daemon off;"]
