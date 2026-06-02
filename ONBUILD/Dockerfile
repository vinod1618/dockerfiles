FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# this instruction runs when someone use this image
ONBUILD copy index.html /usr/share/nginx/html/

CMD ["nginx","-g","deamon-off;"]