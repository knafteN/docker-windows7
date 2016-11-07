# docker-windows7
How to use docker on windows 7.

# About
Docker (https://www.docker.com/) won't work on window 7 machines so here is a step-by-step tutorial on making it work :)

# Download VirtualBox and Ubuntu Server
https://virtualbox.org
https://www.ubuntu.com/download/server

# Install SSH
* `sudo apt-get install openssh-server`
* `sudo /etc/init.d/ssh restart` 

# Share host folder
* `sudo apt-get install virtualbox-guest-additions-iso`
* `sudo apt-get install virtualbox-guest-dkms`
* restart guest OS
* `sudo adduser yourusername vboxsf`

# Forward ports
ssh TCP Host 127.0.0.2:22 Guest 10.0.2.15 22

# Install docker \o/
* `sudo apt-get install docker.io`
* enjoy :-)
