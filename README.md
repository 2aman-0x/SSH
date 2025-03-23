## What is SSH?
SSH or Shell is a network communication protocal that enables two computers/devices to communicate and share data


## WHy it is called as secure shell?
Because communication between host and client will be in encrypt format.

## More about SSH
The default port for SSH client connections is 22  
We can change the default port and use one between 1024 and 32,767  
SSH is also a command in Linux.  
It is used to access an another Linux server or accessing a Linux server from a terminal.  
__Syntax:__ ```ssh user_name@host(ip/Domain_name)```  
__Example:__```ssh goku@192.168.0.114```  

## How to use SSH?
To use SSH, ssh service must be installed on linux server  
You can check using ```rpm -qa | grep ssh,``` or check the file ```/etc/ssh/sshd_config```  
If not already installed then install below to ```install openssh_clients openssh-server```  
and now enable the ssh or check if it is enabled using ```systemctl status sshd```  





