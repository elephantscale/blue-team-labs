# Lab setup

* For the virtual machine to run the lab, you will be given an IP and the password. 

![](images/image_01.png)

* You will click on VNC access and enter the password. You will then have access to an Ubuntu VM.

![](images/image_02.png)

### Background information

* We will be using Goat security labs, described [here](https://owasp.org/www-project-webgoat/)

* However, it comes with security warning. Therefore, this is an instruction on running the labs securely.

## Instructions on running the labs

### Start the Docker

1. SSH into the VM you are given
2. Enter the following

   `docker run -p 8080:8080 -p 9090:9090 -p 81:8888 -e TZ=Europe/Amsterdam webgoat/goatandwolf:latest`

### Start the goat labs

1. Enter the IP of the VM given to you into the browser

![](../images/goat_01.png)

2. Click on SECURE ACCESS VIA HTTPS
3. Enter the password provided to you. You will see the sandbox.
5. Open the browser and enter `localhost:8080/WebGoat`
6. You are ready to go
   
* FYI Goal Labs solutions: https://github.com/WebGoat/WebGoat/wiki/(Almost)-Fully-Documented-Solution-(en)

## Instructor:

* Every student gets this
* ubuntu-clean-desktop-v1
