This is a test pipeline for vagrant-jenkins. This is not a ready or full version.

What will this do:

1. Initialize Vagrant - Completed. 
2. Setup a VagrantFile - Completed with port forward to 8082. 
3. Reference a CentOS box - 
    Accessed Centos from here - https://atlas.hashicorp.com/centos/boxes/7. 
    Picked Virtual box init. 
4. Initialize using CentOS - Completed. Installed CentOs-7
5. Perform Vagrant up - Complete. 
6. Once Vagrant is up, install Java - Installed
    cmd: sudo yum install java. Java version is:
    openjdk version "1.8.0_65"
    OpenJDK Runtime Environment (build 1.8.0_65-b17)
    OpenJDK 64-Bit Server VM (build 25.65-b01, mixed mode)
    Wget not installed, cmd: sudo yum install wget
7. Install jenkins. 
    Add the Jenkins repository to the yum repos, and install Jenkins from here:
    sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/jenkins.repo
    sudo rpm --import https://jenkins-ci.org/redhat/jenkins-ci.org.key
    sudo yum install jenkins
8. Port foward from guest 8080 to 8082 on host. 
9. Validate Jenkins is working. 
10. Initalize plugin's - GitHub Plugin, Git Plugin, Pipeline Plugin. 
11. Connect Jenkins to GitHub. 
12. Push change to game-of-life
13. Run builds and tests on code-commit. 
14. Fail a build. 
15. Run again. 

Issues to be resolved:
1. How to get .gitignore to ignore .vagrant file. Adding .vagrant is not working - Open
2. 
