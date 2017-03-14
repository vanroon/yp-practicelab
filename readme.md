# YP Practice Lab 
**Prerequisites (Get this before the practice lab starts)**

Things you need to get started:
1) A VM with Linux (any choice):
 * VirtualBox (<a href>https://www.virtualbox.org/wiki/Linux_Downloads</a>)
 * Linux (e.g. Ubuntu <a href>https://www.ubuntu.com/download/desktop</a>)
2) On your Linux machine, install the following:
 * Git
```
    sudo apt-get install git
```
 * Docker
   * <a href>https://docs.docker.com/engine/installation</a>

## Contents of this repository
* ~~dockerfiles/tomcat/Dockerfile.yml~~
 * ~~tomcat-users.xml~~
* ~~dockerfiles/docker-compose.yml~~
* ~~spring-petclinic~~
 
## Setup

**We do this during the practice lab**
1. Pull Jenkins docker image
2. Edit **/dockerfiles/tomcat/tomcat-users.xml
3. Build Tomcat docker image 
4. Run Rancher server
```
    sudo docker run -d --restart=unless-stopped -p 8080:8080 rancher/server
```
5. Create docker-compose.yml file
6. Create host
7. Create Rancher stack
8. Test service access
   * Unlock Jenkins
   * Check Tomcat access
9. Start building!


