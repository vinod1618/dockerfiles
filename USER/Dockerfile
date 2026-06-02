FROM almalinux:9
RUN dnf install nginx -y
#root access required to create the user.
RUN useradd roboshop
#upto above we need the root access to perform the commands

USER roboshop  # this will change the container runs under roboshop account and the subsequent commands run under the roboshop user.
CMD ["sleep","200"]