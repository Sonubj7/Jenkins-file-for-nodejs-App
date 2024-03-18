# Jenkins-pipeline-script-Nodejs Application

Create a jenkins file script for a nodejs application

## Prerequisites
1. Create  an server and install jenkins
2. Connect to the jenkins via browser



- INSTALL JAVA    

   `sudo yum install java-11-openjdk`

- ADD JENKINS REPO

  `sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo`

- INSTALL JENKINS
`sudo yum install jenkins`


- START AND ENABLE JENKINS SERVICE
`sudo systemctl start jenkins`
`sudo systemctl enable jenkins`

- LOGIN VIA BROWSER
 `http://your_server_ip:8080`

- INITIAL PASSWORD
 `sudo cat /var/lib/jenkins/secrets/initialAdminPassword`

## To deploy

In order to deploy your application to another server make sure the following

1. install java 
2. Create a directory for uploading the file eg:. jenkins
3. Provide permission for the folder
4. Install nodejs 

