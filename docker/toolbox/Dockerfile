FROM centos
RUN yum install -y httpd && yum install net-tools -y 
RUN yum install -y stress
RUN echo 'Hello Docker Apache v.1' > /var/www/html/index.html
CMD ["/usr/sbin/httpd","-DFOREGROUND"]
EXPOSE 80
