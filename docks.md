How to Install and Configure Docker on Ubuntu 20.04

Docker is a container based on the “Platform as a Service” software application. Docker uses virtualization technology to provide isolated containers for software and tools. These containers use well-defined channels to communicate with each other. This article will show you the easiest way to install Docker on Ubuntu 20.04 and get it running in less than 5 minutes.

	This simple tutorial will show you how to download Docker, enable or disable Docker upon 	system reboot/startup, and change usage permissions for users in six easy steps.

	Step 1:to step-4 Update APT
	As always, first, update and upgrade your APT.

	$ sudo apt update
	$ sudo apt upgrade
	$ sudo apt install docker.io
	$ sudo systemctl enable --now docker
	$ sudo systemctl disable --now docker

	Step 5: Check Docker Version
	You can check the version of Docker with the following command.

	$ docker --version
	
	Step 6: Test Docker
	Test Docker by running the following command, which will open a container to run the Hello 		World command.

	$ docker run hello-world
