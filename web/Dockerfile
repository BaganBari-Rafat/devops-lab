# Start from the official nginx image (on Alpine Linux, which is very small)
FROM nginx:alpine

# Copy our web page into the folder nginx serves from
COPY index.html /usr/share/nginx/html/index.html

# Document which port the app listens on
EXPOSE 80
