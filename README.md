# django-docker-aws
Pre-requiste to the workshop2 repo.

This was used to:

  - create an AWS account, 
  
  - set security groups, 
  
  - create encrypted key pair,
  
  - launch EC2 instance, 
  
  - set an Elastic IP, 
  
  - set IAM roles to communicate with Docker, 
  
  - create an ECR repo, 
  
  - connect to a SSH session via bash terminal with the encrpypted key and: 
  
    - download and install Docker and Docker Compose to the EC2 instance, 

    - download and install AWS CLI in EC2 instance, 

    - create a GitHub repo, 

    - clone GitHub repo to EC2 instance in SHH session, 

    - build Docker image, 

    - run conaitinerized django_docker_aws app, 

    - push images to ECR repo 
