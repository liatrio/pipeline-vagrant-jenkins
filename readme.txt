This is a test pipeline for vagrant-jenkins. This is not a ready or full version.

What will this do:

1. Initialize Vagrant. 
2. Setup a VagrantFile. 
3. Reference a CentOS box. 
4. Initialize using CentOS. 
5. Perform Vagrant up. 
6. Once Vagrant is up, install openjre & open jdk
7. Install jenkins. 
8. Port foward from guest 8080 to 8082 on host. 
9. Validate Jenkins is working. 
10. Initalize plugin's - GitHub Plugin, Git Plugin, Pipeline Plugin. 
11. Connect Jenkins to GitHub. 
12. Push change to game-of-life
13. Run builds and tests on code-commit. 
14. Fail a build. 
15. Run again. 
