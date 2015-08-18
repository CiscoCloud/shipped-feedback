

# Project Shipped FAQ

**Table of Contents**

- [How do I update this FAQ?](#user-content-how-do-i-update-this-faq)
- [Is there a live chat for Shipped?](#user-content-is-there-a-live-chat-for-shipped)
- [Welcome to Shipped UI](#user-content-welcome-to-shipped-ui)
	- [Is Shipped UI free?](#user-content-is-shipped-ui-free)
	- [What is Shipped UI?](#user-content-what-is-shipped-ui)
	- [Where can I find the Shipped UI?](#user-content-where-can-i-find-the-shipped-ui)
	- [Why does Shipped UI need access to my Github Account?](#user-content-why-does-shipped-need-access-to-my-github-account)
	- [Do I need to install Shipped CLI](#user-content-do-i-need-to-install-shipped-cli)
- [Shared Technologies](#user-content-shared-technologies)
	- [What is Github?](#user-content-what-is-github)
	- [What is Docker?](#user-content-what-is-docker)
	- [What is Vagrant?](#user-content-what-is-vagrant)
	- [What is Virtual Box?](#user-content-what-is-virtual-box)
- [Learning Labs](#user-content-shipped-learning-labs)
	- [Where are Learning Labs?](#user-content-where-are-learning-labs)
- [Shipped CLI](#user-content-shipped-cli)
	- [What is Shipped CLI?](#user-content-what-is-shipped-cli)
	- [How to download Shipped CLI?](#user-content-how-to-download-shipped-cli)
- [Shipped API](#user-content-shipped-api)
	- [What is Shipped API?](#user-content-what-is-shipped-api)	
	
###How do I update this FAQ?

If you have a change you would like to submit to this FAQ, please create an [Issue](https://github.com/CiscoCloud/shipped-feedback/issues) in our [Shipped Feedback](https://github.com/CiscoCloud/shipped-feedback) project and let us know. Be sure to specify FAQ in the title.

### Is there a Live Chat for Shipped
Q: Is there a live chat where I can learn more, or "talk shop" about Shipped?  
A: Yes, Shipped has a live chat you can join. It is hosted on Glitter! [![Join the chat at https://gitter.im/CiscoCloud/shipped-feedback](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/CiscoCloud/shipped-feedback?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Welcome to Shipped UI ##

### Is Shipped UI free ###

Yes. Shipped UI is free for you to use. Please give it a try, and tell your friend!

### What is Shipped UI? ###
Shipped is a Cisco Development Portal which provides us with an integrated development environment for creating, building, testing, and deploying into the Cisco Cloud in a continuous integration environment.  


### Where can I find the Shipped UI? ###  

Follow this link to the find [Shipped UI Development Portal](http://ciscocloud.github.io/shipped/dist/#)

### Why does Shipped UI need access to my Github Account ###

Shipped is very tightly integrated with Github to offer you a highly integrated Constant Integreation / Constand Development environment.

### Do I need to install Shipped CLI ###

Our current implementation requires you install the [Shipped CLI](#user-content-what-is-shipped-cli) before bootstrapping your first Shipped project as the bootstrap process is managed by the Shipped CLI

## Shared Technologies ##

### What is Github ###

GitHub is a Web-based Git repository hosting service. Shipped supports GitHub Repositories for source code version control. [GitHub](https://help.github.com/) offers distributed revision control and source code management. GitHub provides a web-based graphical interface with desktop and mobile integration. GitHub offers both private and public repositories.   

### What is Docker ### 

Shipped provides the means to quickly create custom [Docker](https://docs.docker.com/) Containers. Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Docker uses resource isolation features of the Linux kernel such as cgroups and kernel namespaces to allow independent "containers" to run within a single Linux instance, avoiding the overhead of starting and maintaining virtual machines.

### What is Virtual Box ###  
  
Shipped leverages Oracle VM [VirtualBox](https://www.virtualbox.org/) Hypervisor to host the Docker Containers. VirtualBox may be installed on an existing host operating system; it can create and manage guest virtual machines, each with a guest operating system and its own virtual environment. Many Docker Containers can be hosted within one Virtual Machine in Virtual Box.  

### What is Vagrant ###

Shipped utilizes [Vagrant](https://docs.vagrantup.com/v2/) to help manage the Virtual Machine which hosts the Docker Containers. Vagrant creates and configures virtual development environments. Vagrant utilizes a single file called Vagrantfile to describe the type of machine you want, the software that needs to be configured, and machine access details such as port mapping, etc.   


## Shipped Learning Labs ##

### Where are the Learning Labs

Navigate to our [Shipped UI Development Portal](http://ciscocloud.github.io/shipped/dist/#) or log into the [DevNet Learning Labs](https://developer.cisco.com/site/devnet/learningLabs/overview.gsp) and give [Shipped 100 Intro to Shipped](https://learninglabs.cisco.com/lab/shipped-100-intro-shipped/step/1) a try.

## Shipped CLI ##

### What is Shipped CLI ###

The Shipped CLI is a full featured command-line utility for interacting with Shipped.  

### How to download Shipped CLI ###

curl http://shipped-api.shipped-cisco.com/cli/static/shipped.sh | bash -s

## Shipped API ##

### What is Shipped API ###
 
The Shipped API are a complete API set available for interacting with Shipped via your own custom source code. Read about them at [Shipped API Docs](http://ciscocloud.github.io/shipped/api-docs/build/index.html) and them give them a try. Most of them can be executed using the command line tool 'curl'.

