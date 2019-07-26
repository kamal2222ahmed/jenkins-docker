# jenkins-docker
Automate Jenkins install/setup using Docker

1. $ docker build -t jenkins/jenkins .
2. $ docker run -d --name jenkins-server -p 8080:8080 jenkins/jenkins
3. open http://localhost:8080
4. Login as admin/admin
