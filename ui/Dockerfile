# Pull nginx base image
FROM nginx:1.19.6

# Copy static assets into var/www
COPY ./build/ /usr/share/nginx/html/

# Copy nginx config
COPY nginx.conf /etc/nginx/nginx.conf
