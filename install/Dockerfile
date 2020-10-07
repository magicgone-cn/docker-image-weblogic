FROM oraclelinux:6.8
COPY wls1036_linux32.bin /usr/weblogic/
RUN yum install -y glibc.i686
ENV USER_MEM_ARGS -Xms1024m -Xmx1024m -XX:PermSize=256m -XX:MaxPermSize=256m
EXPOSE 7001
