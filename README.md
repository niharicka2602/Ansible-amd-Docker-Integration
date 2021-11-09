<h1 align="center">Ansible-and-Docker-Integration 👋</h1>


> Building Ansible playbook to configure docker and running HTTPD service inside the container.<br /> `docker.yml` will take care of all the **yum** configurations.

## ✨ Build Status

`docker.yml` file is completed.

<br/>


## ‼ Requirements 

- A Controller Node 
- A Target Node
- Internet Connectivity
<br/>

## 💻 Technologies Used
<p align="left"> 
    <a href="https://www.ansible.com/"> <img src="https://img.icons8.com/fluency/48/000000/ansible.png"/> </a>
    <a href="https://www.docker.com/"/> <img src="https://img.icons8.com/fluency/48/000000/docker.png"/> </a>
</p><br/> 


## 🚀 Execution

Make sure you have [ansible](https://www.ansible.com/) & [docker](https://www.docker.com/) installed 
Also install the following dependencies:
- Docker SDK
- HTTPD
<br />
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
➼ To access the wepage inside the container:

```sh
curl 192.168.1.0
```
<br/>


## Video

[![Ansible And Docker Basics](https://img.youtube.com/vi/Sf8urGA-Yhs/0.jpg)](https://youtu.be/Sf8urGA-Yhs)


## 📸 Screenshots

<a><img src="https://miro.medium.com/max/3726/1*gBZXnSM3qnlOuWymN-kl_g.png"></a>
<br /><br />
<a><img src="https://miro.medium.com/max/3720/1*7ddDlGW_NkuY1g2vnQeCMQ.png"></a>



##  🤝 Code Contributors

This project exists thanks to all the people who contribute.
<a href="https://github.com/niharicka2602/Ansible-and-Docker-Integration/graphs/contributors"><br /><img src="https://github.com/niharicka2602/Ansible-and-Docker-Integration/blob/main/me.ICO" /></a>
<br /> <br />


## 💢 Contributing

Contributions, issues and feature requests are welcome.<br />
Feel free to check [issues page](https://github.com/niharicka2602/Ansible-and-Docker-Integration/issues) if you want to contribute.<br />
[Check the contributing guide](https://github.com/niharicka2602/Ansible-and-Docker-Integration/blob/main/Contributing.md).<br /> <br />


## 👩‍⚖️ Author

👤 **NIHARIKA DHANIK**

- Twitter: [Niharika](https://twitter.com/FranckAbgrall)
- Github: [niharicka2602](https://github.com/niharicka2602?tab=repositories)
- Blog : [Niharika Dhanik](https://niharicka.medium.com/configure-docker-services-using-ansible-playbooks-8edf325380dc)
<br/>


## Show your support

Please ⭐️ this repository if this project helped you!
<br/> <br />


## 📝 License

Copyright © 2021 [Niharika Dhanik](https://github.com/niharicka2602?tab=repositories).<br />
This project is [MIT](https://github.com/niharicka2602/Ansible-and-Docker-Integration/blob/main/License) licensed.

---


