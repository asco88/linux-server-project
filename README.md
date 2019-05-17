## linux-server-project

# IP address
http://35.158.225.250.xip.io

# Installed Software
 - i used python3 in order to run create the catalog-app project
 - i also used xip.io software in order to create a custom DNS server which allowed me authenticating Google login in the catalog-app project

# Linux Configuration
I used AWS Lightsail in order to host a new Ubuntu 16.0 server.
The firewall is configured to allow connections only to ports 2200/ssh, 80/HTTP, 123
A new user is created: grader
The grader user is configured with root permissions
An SSH key pair was created in order to allow access to the server to login with grader user
Connecting to the server using ssh connection using password is disabled

