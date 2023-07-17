# Devopscapstoneproject2

# Devopsproject2

![architecture](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/f3145072-c6c3-4d75-9f85-922a0213e477)

Implemented a DevOps lifecycle such that all the requirements are implemented without any change in the Docker containers in the testing environment.
CodeBuild is triggered once the commits are made in the master branch.
The code is containerized with the help of the Dockerfile. The Dockerfile is built every time there is a push to GitHub.
Used Kubernetes cluster and the containerized code from Docker Hub is deployed with 2 replicas. Created a NodePort service and configure port 30008.
Created a Jenkins pipeline script to accomplish the above task.


	Create an Ec2 instance for master-server

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/78e8d2f1-3e53-4794-b6af-83a1e35eed0f)

	Download terraform
	Make main.tf file for creating 3 t2.medium instance 

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/fb04b9a0-8867-4ebe-a255-a9f4bfe4fd63)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/c1172ec9-44c9-423c-bf7f-93dcfd0ba529)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/6a3e19d8-63a5-4e12-af12-4e31d22bb90b)

	Install docker and kubeadm, kubelet, and kubectl in Kubernetes master as well as worker nodes and install java in Kubernetes master.

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/5dbad39c-1165-4971-a3df-d383339a4109)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/4a358147-9160-4dc7-9278-d9086ace81cb)

	Run “kubeadm init” command in master node and join the workers node to paste join commands

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/6cf7e67f-8193-4141-b9ee-bf50a26bfe16)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/36cf612f-1f9e-43e4-bcf2-9f9738983d63)

	In Kubernetes master run the following command to check nodes

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/d8721b32-580a-487e-b809-64900f76524d)

	In Master-server install Jenkins and java

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/21f6473e-9d23-429a-81d8-3362ffc637e5)

	Setup Jenkins

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/b3e5d813-9cdf-4e1f-b6ec-1e0e5ddaedc1)

	Set the Kubernetes master node in jenkins

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/f9368531-0125-4f5b-8827-f31195ac38a9)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/8429fb14-a9c9-49ba-afa5-ac9a2580a374)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/d30e4230-52d1-418b-ad96-0f0dfbdc6545)

	Set the credentials for the docker hub account

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/31715105-fd6e-4083-90fa-b946bef641f4)

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/3799b714-c667-4c3b-8e45-ea1cc56a77d9)

	Create a pipeline 

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/838cd7cd-fa6f-4542-ac2c-9b74b6846881)

	Write the script

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/49ef956b-ef41-45e5-9139-2725f2db5e40)

	And build

![image](https://github.com/Tripti-TD/Devopsproject2/assets/128075759/39e06fde-e567-438d-9a77-190a9e18ae93)

Please excuse me if something is missed.
