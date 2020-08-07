FROM ubuntu:14.04
MAINTAINER xiaohuashifu "827032783@qq.com"
RUN apt-get update && apt-get install -y nginx
RUN echo 'Hi, I am in your container' > /usr/share/nginx/html/index.html
ENTRYPOINT ["/usr/sbin/nginx"]
LABEL version="1.0"
LABEL location="cn" type="data"
EXPOSE 80
