# Ansible-amd-Docker-Integration
Building Ansible playbook to configure docker and running HTTPD service inside the container
<br>
The following Plays are executed by the Ansible PlayBook in the Target Node —<br>
➼ Create a yum repository to configure Docker
➼ Execute commands to install Docker
➼ Check for Docker Package
➼ Enable Docker Services
➼ Install Docker SDK
➼ Pull the required image (here — vimal13/apache-webserver-php:v1) from the Docker Hub
➼ Run the docker container and expose it to the public
➼ Initiate HTTPD on Docker (optional)
➼ Get Container Details (optional)
➼ Copy File To Docker Container
➼ Copy the html code from Controller Node to "/var/www/html" directory inside the newly launched Docker Container
➼ Access the webpage using “curl” command inside the container
