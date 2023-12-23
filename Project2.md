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

### Accessing web server over the internet using public IP

[url with public IP](http://51.20.60.0)

![accessing server over the internet in HTML](./Images/welcome-to-nginx.png)


## Installing mysql

### installing mysql using apt

`sudo apt install mysql-server`

![installing mysql](./Images/installing-mysql.png)

### Logging into mysql console

`sudo mysql`

![mysql console](./Images/mysql-console.png)

### setting a password for the root user, using mysql_native_password as default authentication method

`ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '******';`

![mysql native password](./images/sql-password.png)

### Exiting mysql console

`exit`

![exiting mysql shell](./images/mysql-exit.png)

### Running interactive security script to lockdown access on database

`sudo mysql_secure_installation`

### A strong mysql_native_password was maintained!

![mysql native passsword](./images/secure-installation.png)

### Testing logon access to mysql console

`sudo mysql -p`

![logon successful](./images/mysql-logon.png)

### Exiting mysql console again:

`exit`

![exiting mysql shell](./images/mysql-exit.png)



