# setting base image
FROM centos:centos6

# Author
MAINTAINER iikura

# install Apache http server
RUN ["yum",  "-y", "install", "httpd"]

# start httpd
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

