FROM ubuntu
RUN apt update -y
RUN apt install nginx -y
CMD /usr/sbin/nginx -g "daemon off;"
LABEL owner="naveen"\
      maintainer="bommakanti"
EXPOSE 80