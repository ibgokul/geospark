This is a simple devops project on deploying a Web Application to tomcat Server.

Steps involved.

Source code Repository: Github

Tools used

Ansible(Automation)
Docker(Container)
Jenkins(CI/CD)
Server image- Amazone Linux


-> Whenever there is change in the github repository thrrough webhooks and Jenkins poll SCM it will automatically detect
the changes and build happens automatically.

-> Jenkins server is connected with Ansible and docker Servers through SSH

-> in the above step, ansible will create docker image, run the container and remove the image and deploy the web application to 
tomcat server in port 8080