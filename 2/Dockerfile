FROM httpd:latest
WORKDIR /usr/local/apache2
COPY index.html ./htdocs/
COPY httpd.conf ./conf/
EXPOSE 9999
ENV CONTAINER=docker
CMD ["sh", "-c", "echo $CONTAINER && httpd-foreground"]


