FROM centos
RUN yum install -y httpd && yum install net-tools -y && yum install stress -y
RUN echo 'Hello Docker Apache v.1' > /var/www/html/index.html
CMD ["/usr/sbin/httpd","-DFOREGROUND"]
EXPOSE 80
