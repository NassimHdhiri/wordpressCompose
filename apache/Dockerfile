FROM httpd:latest

# Copy custom configuration files
COPY ./config/httpd.conf /usr/local/apache2/conf/httpd.conf

# Copy website content to the web server root
COPY ./html/ /usr/local/apache2/htdocs/

# Expose port 80 for web traffic
EXPOSE 80