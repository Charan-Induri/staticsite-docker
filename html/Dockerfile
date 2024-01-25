FROM nginx
RUN apt update -y
RUN apt install apche2 -y
RUN echo "<h4> Happy Birthday Lavvvv </h4>" > /var/www/html/index.html
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
