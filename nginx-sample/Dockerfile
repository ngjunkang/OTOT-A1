# Using the latest nginx
FROM nginx:latest

# Overwrites the default index.html with our index.html
COPY ./index.html /usr/share/nginx/html/index.html

# Overwrites nginx default configuration file
COPY ./default.conf /etc/nginx/conf.d/default.conf
