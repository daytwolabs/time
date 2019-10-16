FROM centos:7
MAINTAINER Veer Muchandi veer@redhat.com
RUN yum -y install nc
ADD ./init.sh ./
EXPOSE 8080
CMD ["./init.sh"]
