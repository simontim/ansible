FROM centos:7

MAINTAINER simone.mastrodonato@telecomitalia.it

RUN yum update -y

RUN yum install -y epel-release 
	
RUN yum install -y ansible

RUN yum install -y openssh openssh-server openssh-clients openssl-libs

RUN ssh-keygen -f /root/.ssh/id_rsa
