# Web hosting with Docker

In this project, we providing a Linux environment with Vagrant, where the Docker runs.

Inside the Docker container we're hosting a webpage by nginx.

The webserver's root folder is the website shared folder, and you can modify it's content from the host and  guest too.

!!!On linux system, you may have to change in the Vagratnfile the hosts port from 80 to something higher than 1024!!!

**Base requirements:**

 - git (https://git-scm.com/downloads)
 - Vagrant (https://www.vagrantup.com/downloads)
 - Virtualbox (https://www.virtualbox.org/wiki/Downloads)