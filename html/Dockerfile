FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
RUN echo "<h1> Happy Birthday Lavvvv </h1>" > /var/www/html/index.html
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
