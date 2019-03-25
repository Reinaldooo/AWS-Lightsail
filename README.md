# Cloud Linux Server
#### In this project Amazon Web Services is used to host a Linux server on the cloud  

##### Highlights:
  - Firewall
  - Connections via SSH
  - Apache Web Server

[Live Demo](http://3.92.43.113.xip.io/)

#### Server features
* Built using the principle of least privilege, so a firewall is used to block all ports except 2200 and 80 from remote access.
* Apache server is used to serve the application on port 80, the default to browser access.
* To further improve security, login is only possible using SSH keys, so attackers can't brute force their entrance.

#### Connection
* The best way to connect is using [Putty](https://www.putty.org/), an open source SSH client.
* Port ``2200`` should be used to connect via SSH.
* Server IP: ``3.92.43.113``
* To get your SSH key, contact me at ``rewifetri@gmail.com``