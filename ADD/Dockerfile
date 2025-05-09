FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/cekharchandra-devops/202-roboshoop-documentation/refs/heads/main/01-web.MD /usr/share/nginx/html/index.html
ADD /c/Users/user/Downloads/sample-1.tar /tmp

CMD [ "nginx", "-g", "daemon off;" ]