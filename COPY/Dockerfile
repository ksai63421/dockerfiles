FROM nginx
# removing default html and then copy our html 
RUN rm -rf /usr/share/nginx/html/index.html
#file should be available in current directory where dockerfile exist
COPY index.html /usr/share/nginx/html/index.html