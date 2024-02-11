FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
RUN echo "Hello, welcome to dockerfile a way of creating own images" > /usr/share/nginx/html/hello.html
# daemon off command makes our container running and affected to screen 
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]