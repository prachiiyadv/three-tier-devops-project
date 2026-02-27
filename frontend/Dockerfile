FROM nginx:alpine

# Remove default nginx files
RUN rm -rf /usr/share/nginx/html/*

# Copy our frontend
COPY index.html /usr/share/nginx/html/

# Expose port 8081 instead of 8080
EXPOSE 8081

CMD ["nginx", "-g", "daemon off;"]
