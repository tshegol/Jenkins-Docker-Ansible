# Jenkins-Docker-Ansible
This ansible playbook will install and configure jenkins inside a docker container 

# Run the below command to excute jenkins docker container:

<code>
ansible-playbook jenkins.yml --ask-sudo-pass
</code>

# To check the admin password run the below command:

<code>
docker exec jenkins-blue cat /var/jenkins_home/secrets/initialAdminPassword 
</code>



"I Choose blueocean jenkins, This image can be changed to prefered image on dockerhub eg: jenkins/jenkins:lts etc.

