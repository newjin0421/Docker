FROM centos:7

RUN yum -y install httpd php && yum clean all

ADD src.tar /var/www/html

EXPOSE 80/tcp
VOLUME /var/www/html /var/log/httpd

# ENTRYPOINT /usr/sbin/httpd -D FOREGROUND

# FROM centos:7

# RUN yum -y install httpd mod_wsgi && yum clean all
# COPY vhost.conf /etc/httpd/conf.d
# COPY myapp.wsgi /var/www/html/myapp.wsgi


# VOLUME /var/www/html /var/log/httpd
# EXPOSE 80/tcp

# ENTRYPOINT /usr/sbin/httpd -D FOREGROUND