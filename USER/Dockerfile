FROM almalinux:9
RUN dnf install nginx -y
#root access required to create the user.
RUN useradd roboshop

USER roboshop
CMD ["sleep","200"]