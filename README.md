# linux-server-project

## IP address
http://35.158.225.250.xip.io

## Installed Software
 - i used python3 in order to run create the catalog-app project
 - i also used xip.io software in order to create a custom DNS server which allowed me authenticating Google login in the catalog-app project

## Linux Configuration
I used AWS Lightsail in order to host an Ubuntu 16.0 server.
The firewall is configured to allow connections only to ports 2200/ssh, 80/HTTP, 123,
 SSH connection using default port 22 is denied.
A new user is created: grader
The grader user is configured with root permissions
An SSH key pair was created in order to allow access to the server to login with grader user, the key has no passphrase
Connecting to the server using ssh connection using password is disabled.
Root access is disabled completely to the server

## starting the server
In the grader user there is a file startServer.sh, executing it will start the application and the xip custom DNS application
Currently the server is running.

## using grader
grader has root permissions and in order to use it, it's password is 123

## third party applications
the catalog-app is available in this git repository: https://github.com/asco88/catalog-app
XIP.IO - wildcard DNS provider, available at: http://xip.io/
