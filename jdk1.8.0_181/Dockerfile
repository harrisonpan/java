FROM centos:latest
MAINTAINER "Harrison Pan" <498136095@qq.com>
ADD jdk-8u181-linux-x64.tar.gz /opt
RUN ln -s /opt/jdk1.8.0_181 /opt/jdk \
    && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo 'Asia/Shanghai' > /etc/timezone
ENV JAVA_HOME /opt/jdk
ENV LANG="zh_CN.UTF-8"
ENV PATH $JAVA_HOME/bin:$PATH
CMD java -version
