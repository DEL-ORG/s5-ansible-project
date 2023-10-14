FROM ubuntu:20.04
RUN apt update 
# Set the DEBIAN_FRONTEND environment variable to noninteractive
ENV DEBIAN_FRONTEND=noninteractive
RUN apt install -y curl vim wget ansible  sshpass   git 
RUN  useradd ansible -m -d /home/ansible -s /bin/bash 
# # COPY .ssh /home/ansible
# RUN  chown -R ansible:ansible /home/ansible
# RUN chmod 400 /home/ansible/.ssh 
USER ansible


# RUN  git clone -b eric https://github.com/devopseasylearning/S6-Dockerfile-project.git
# RUN  mv S6-Dockerfile-project/.ssh /home/ansible
