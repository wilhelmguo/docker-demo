FROM centos:7

COPY nginx.repo /etc/yum.repos.d/nginx.repo

RUN yum install -y nginx

EXPOSE 80

ENV HOST=mynginx

CMD ["nginx","-g","daemon off;"]