# cloud-native-monitoring
Used Docker, Kubectl, Amazon EKS, ECR, Boto3 and Python Flask to build a nifty system resource monitor.

Requirements:
1.AWS Account
2.Docker installation
3.Kubectl Installation
4.Configure AWS CLI
5.Boto3 module installation

Note: Install the modules we have used in ecr.py and eks.py

*** Create ECR Repository and Build the dokcer image with (docker build) and push it to repository using the push commands***

***Create the EKS cluster and add the worker nodes by including IAM roles and specific security policies ***

*** Finally do the kubectl port forward in 5000 (used here) and access it in your browser http://localhost:5000/ ***


Note: Used the python psutil module the fetch the memory and cpu values.

