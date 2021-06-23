FROM artifactory.raiffeisen.ru/ext-rbru-osimage-docker/centos:7.9
RUN yum install -y httpd && yum install net-tools -y
RUN echo 'Hello Docker Apache v.1' > /var/www/html/index.html
CMD ["/usr/sbin/httpd","-DFOREGROUND"]
EXPOSE 80
