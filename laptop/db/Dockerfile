FROM centos
MAINTAINER ganesh <ganesh.g@gmail.com>
RUN yum install httpd git -y
RUN git clone https://github.com/Gankidiganeshreddy/begumpet.git /var/www/html
CMD ["httpd","-DFOREGROUND"]

