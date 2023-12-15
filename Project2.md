# PROJECT 2: LEMP STACK IMPLEMENTATION

# Documentation of Project-2

## Installing the nginx web server

`sudo apt update`

![updating server package index](./Images/sudo-apt-update.png)

### Installing Nginx

`sudo apt install nginx`

![installation of nginx](./Images/install-nginx.png)

### To verify that nginx was successfully installed and is running as a service in Ubuntu

`sudo systemctl status nginx`

![nginx status](./Images/status-nginx.png)

### With EC2 configuration open to inbound connection through port 80, server is being accessed locally in Ubuntu shell:

`curl http://localhost:80`

![accessing server locally](./Images/curl-localhost.png)