# DIY Web Application Deployment On a Budget

Time: 3 hours
Class size: max 18 students

## Description

I’m not a professional developer. I’m an artist. That said, I’ve taught myself how to launch web applications on linux servers and want to share what I’ve learned.

### Topics Covered

This workshop will walkthrough the following processes in two sections:

* Local
	* Install and configure NGINX - [guide](./guides/local-nginx.md)
	* HTTPS - [guide](./guides/local-https.md)

* Remote
	* Deploy remotely - [guide](./guides/remote.md):
		* Setup a Linux Virtual Private Server (for cheap)
		* Register a Domain and point it to your server
		* Configure NGINX as a reverse proxy
		* Use Certbot to install tls/ssl certificates
		* Create a simple web application using Python
		* Deploy and manage the site using systemd

### "Prerequisites"

Phew! That’s a lot. You might be wondering if this is too much. We’ll break it down and move to the cloud step by step, but here are a few things that you should feel comfortable doing:

* Work with the CLI (Terminal)
* Experience connecting to "remote" devices/servers via SSH
* Basic HTML

### Software

**Windows Users Beware**: I’m using MacOS for in-class demos and guides and if we make it to deployment, will be working with Debian Linux. You should be able to follow along using installation guides for Windows. Directories on your systems may vary from those in teh guides. 

Some applications that would be nice to have setup ahead of time:

* Python3 (latest)
* A text editor or IDE of your choice. I’ll be using Sublime and nano.
* Git
* rsync
