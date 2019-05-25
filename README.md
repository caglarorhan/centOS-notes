**CentOS Notes (CentOS 7+) For Digital Ocean**



**SSH and PuTTY Configuration**

Create a SSH private and public key couple with PuTTY Key Generator. Keep them safe!

Add the keys to Digital Ocean (copy the key body from inside PuTTY Key Generator).
Digital Ocean -> left menu -> Security , in the page SSH-Keys area, Add SSH Key button.

After that you can log in with PuTTY as shown in images below!





![PuttY-Key-Generator-1](https://github.com/caglarorhan/centOS-notes/blob/master/img/Putty-Key-Generator-1.JPG)

![PuttY-Key-Generator-2](https://github.com/caglarorhan/centOS-notes/blob/master/img/Putty-Key-Generator-2.JPG)




![PuttY-1](https://github.com/caglarorhan/centOS-notes/blob/master/img/Putty-1.JPG)

![PuttY-2](https://github.com/caglarorhan/centOS-notes/blob/master/img/Putty-2.JPG)

![PuttY-3](https://github.com/caglarorhan/centOS-notes/blob/master/img/Putty-3.JPG)

**How to install NodeJS to CentOS**

- In CentOS first install `wget` with using `yum install wget`.

- Change directory to login directory with `cd ~`

- After this. Find latest - or LTS - node versions source. Look **nodejs.org** for this. Today its 
https://nodejs.org/dist/v12.3.1/node-v12.3.1.tar.gz for me.

- Export content of this file into /usr/local directory with `tar --strip-components 1 -xzvf node-v* -C /usr/local`

- You can remove `node-v12.3.1.tar.gz` from `~` with `rm node-v12.3.1.tar.gz `



