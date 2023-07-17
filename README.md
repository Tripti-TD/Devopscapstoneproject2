# Devopscapstoneproject2

# Devopsproject2
![architecture](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/444d4ab9-9827-49ab-a2e5-f2f1e6ada48f)


Implemented a DevOps lifecycle such that all the requirements are implemented without any change in the Docker containers in the testing environment.
CodeBuild is triggered once the commits are made in the master branch.
The code is containerized with the help of the Dockerfile. The Dockerfile is built every time there is a push to GitHub.
Used Kubernetes cluster and the containerized code from Docker Hub is deployed with 2 replicas. Created a NodePort service and configure port 30008.
Created a Jenkins pipeline script to accomplish the above task.


	Create an Ec2 instance for master-server

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/52411fe7-a0a5-49f9-9006-358f69f67b29)

	Download terraform
	Make main.tf file for creating 3 t2.medium instance

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/556b1247-b9dd-4546-a94f-f7059d00866b)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/4d98dd46-0940-4b25-9bf4-616e9e7d6f5f)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/3c83966a-d9b5-43f8-a041-a0eeba71f050)

	Install docker and kubeadm, kubelet, and kubectl in kuberenetes master as well as worker nodes and install java in kubernetes master.

 ![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/4f1e944e-6557-42e4-81f2-0caad8804778)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/a86b551a-6640-4416-9a3b-b8ee69ba39a8)
 
	Run “kubeadm init” command in master node and join the workers node to paste join commands

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/8e1a6876-a011-442a-83eb-13ca27baf0d3)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/943370c2-a323-4abf-b271-bb6bb5582919)

	In Kuberenetes master run the following command to check nodes

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/ba1dee22-cc65-4c66-a7f4-d82dd7b1593a)

	In Master-server install Jenkins and java

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/6896237f-be87-4d86-9769-378202f25cf8)

	Setup Jenkins

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/b90332fc-3f19-4d94-856d-bce9e7ff5da0)

	Set the Kubernetes master node in Jenkins

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/52b71260-877e-45b1-b95b-3a88750b6ec7)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/3265162c-12ea-48fd-ab9b-bcfefe6f0b96)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/b18bc219-74b2-4693-bcf6-aec04928aa1a)

	Set the credentials for docker-hub account 

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/239a9d98-2346-4fbb-8419-074a432e8d98)

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/aafd0abf-e4c3-489c-9628-3b7d4d857750)

	Create a pipeline 

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/0d2d903f-3257-4d4d-bb6f-095e8c86a3ea)

	Write the script

 ![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/2e764fb1-3bbb-4f1f-b398-4d3dce577724)
 
	And build

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/31b46e4c-0991-45d8-9a0e-879837c57261)

	Docker-Hub

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/bd9ef290-bdb9-47d6-80ee-958a8898a6e3)


	The Webpage

![image](https://github.com/Tripti-TD/Devopscapstoneproject2/assets/128075759/9e2d7e92-b714-4a4f-a185-058c4d2e9981)

Note: Please excuse if something missed.
