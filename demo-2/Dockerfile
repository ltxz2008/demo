FROM lucky-starry001.server/library/java:8u172-jre-alpine
MAINTAINER ltxz2008 <duanzongxiang@gmail.com>

#设置系统编码
ENV LANG=en_US.UTF-8 \
    LANGUAGE=en_US.UTF-8

ADD ./target/demo.jar /app/
CMD ["java", "-Xmx200m", "-Djava.security.egd=file:/dev/./urandom","-jar","/app/demo.jar"]

EXPOSE 8080