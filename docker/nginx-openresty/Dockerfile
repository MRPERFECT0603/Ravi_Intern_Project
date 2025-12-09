FROM openresty/openresty:1.21.4.1-0-alpine

# Copy your proxy configuration
COPY nginx.conf /usr/local/openresty/nginx/conf/nginx.conf

EXPOSE 80

CMD ["/usr/local/openresty/bin/openresty", "-g", "daemon off;"]FROM openresty/openresty:1.21.4.1-0-alpine

