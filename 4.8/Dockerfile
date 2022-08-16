FROM centos:centos7
# Commands to update the image
RUN yum install gcc 4.8.5
RUN yum install gcc-c++ 4.8.5
RUN yum install make
RUN yum install glibc-devel.i686
RUN yum install libgcc.i686 
RUN yum install libstdc++-devel.i686

# LANG,LOCALTIME
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
