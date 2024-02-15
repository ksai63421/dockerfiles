FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello, welcome to dockerfile a way of creating own images" > /usr/share/nginx/html/hello.html
RUN yum install git -y
RUN yum install maven -y 
# daemon off command makes our container running and affected to screen
CMD [ "nginx", "-g", "daemon off;" ]