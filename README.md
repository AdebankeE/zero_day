@title GETTING STARTED WITH VAGRANT
 This is me learning to set up my local machine
-HOW TO INSTALL VAGRANT
Download VirtualBox from this link
Install VirtualBox
Download Vagrant from this link
Install Vagrant
Open the command prompt
Add the Ubuntu 20.04 (Focal) image to your box list:
C:\Users\julien> vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here

Create your first virtual machine:
C:\Users\julien> vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" -you don’t have to execute this command line everyday, only once, to create a new virtual machine 
C:\Users\julien> vagrant plugin install vagrant-vbguest -> to avoid issue with the last version of Vagrant (2.2.4 or latest)
C:\Users\julien> vagrant up -> it will start your virtual machine 
C:\Users\julien> vagrant ssh -> now you are inside your virtual machine. 

