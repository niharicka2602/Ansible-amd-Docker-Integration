# Ansible-amd-Docker-Integration
Building Ansible playbook to configure docker and running HTTPD service inside the container
<br><br>
The following Plays are executed by the Ansible PlayBook in the Target Node — <br>
➼ Create a yum repository to configure Docker <br>
➼ Execute commands to install Docker <br>
➼ Check for Docker Package <br>
➼ Enable Docker Services
➼ Install Docker SDK <br>
➼ Pull the required image (here — vimal13/apache-webserver-php:v1) from the Docker Hub <br>
➼ Run the docker container and expose it to the public <br>
➼ Initiate HTTPD on Docker (optional) <br>
➼ Get Container Details (optional) <br>
➼ Copy File To Docker Container <br>
➼ Copy the html code from Controller Node to "/var/www/html" directory inside the newly launched Docker Container <br>
➼ Access the webpage using “curl” command inside the container <br>
<br><br>
For detailed blog visit-- 
<br> https://niharicka.medium.com/configure-docker-services-using-ansible-playbooks-8edf325380dc <br>
