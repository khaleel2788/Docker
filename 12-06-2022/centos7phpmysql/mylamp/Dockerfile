FROM centos:7
LABEL purpose="classroom" author="khaleel"
RUN yum update -y && yum install php php-mysql -y && systemctl enable httpd.service
EXPOSE 80
CMD ["sleep", "1d"]
