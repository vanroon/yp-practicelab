# YP Practice Lab
Things you need to get started:
* A VM with Linux (any choice) and:
 * Git
 * Docker

## Contents of this repository
* dockerfiles/jenkins/Dockerfile.yml
* ~~dockerfiles/tomcat/Dockerfile.yml~~
 * ~~tomcat-users.xml~~
* ~~dockerfiles/docker-compose.yml~~
* PetClinic?
 
## Setup
1. Build Jenkins docker image
 * Set permissions on Jenkins volume:
```
sudo chown -R 1000 /home/<username>/jenkins_home
```
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


