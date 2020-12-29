# Ansible playbook to install docker and create an httpd container - 3 different ways

Playbook to :
- Install docker service on ubuntu
- Pull a httpd image 
- create a httpd docker container

## ansible.cfg
Custom configuration file for this project


docker_apache.yml

Here install docker and create a httpd docker container and upload custom httpd conf file

docker_image.yml

In this playbook, created an image from Dockerfile and uploaded the same to docker hub

docker_test.yml

Simple playbook to create apache container
