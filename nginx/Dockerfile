FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy built frontend once built:
COPY build/ /usr/share/nginx/html
