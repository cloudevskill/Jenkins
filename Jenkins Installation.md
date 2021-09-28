Prerequisites 
Java is a prerequisite for installing Jenkins

  #To Verify Java Installation 
  
  	java --version
	
#Download and Install Jenkins Application 

This command is used to add the Jenkins public key to the system. 

	sudo wget -O /etc/yum.repos.d/jenkins.repo \https://pkg.jenkins.io/redhat-stable/jenkins.repo
	
Run the below command to add the Jenkins repository to your system

	sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

Run the below command to update 

	sudo yum upgrade

Run the below command to Install Java and epel
	
	sudo yum install epel-release java-11-openjdk-devel

Below command will Install Jenkins 

	sudo yum install jenkins

Restart service 
	
	sudo systemctl daemon-reload

	
