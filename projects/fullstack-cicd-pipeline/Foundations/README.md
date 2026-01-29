# Devops Foundations

DevOps is a cultural and technical movement that bridges the gap between software development (Dev) and IT operations (Ops). It emphasizes collaboration, automation, continuous integration, continuous delivery, and monitoring throughout the software development lifecycle.

# The Roadmap

1. Networking
2. Linux
3. Cloud
4. Docker
5. Kubernetes
6. CICD ( Jenkins, Gitlab, Github actions- any of these )
7. Infrastructure as Code ( IAC )

# Why the order can be like this ?

1. Networking is the main thing behind System Administration , Cloud Engineering, Devops, SREs.
   Things to learn :
   Public vs Private IP

2. Linux is the backbone of engineering. Everything is built on top of Linux.
   Things to Learn :
   a) Basic Commands, learning to write in vi,vim,nano editors
   b) Linux File system
   c) Ownership control
   d) User level permissions
   e) Security ( Passwordless authentication )
   f) Understand the importance of Cron Job

3. Cloud
   a) Try the networking, linux commands by spinning up an a VM in any cloud under free tier
   b) Create a new user inside the VM
   c) Provide the necessary permissions for that
   d) Try writing a basic script like creating a file and deploying it
   e) Create a cron job and refer the deployment file in the cronjob

4. Docker ( Containerisation )
   a) Understand VM vs Containers and the importance of Containers in the modern technologies
   b) Install Docker desktop in your local PC/Laptop
   c) Learn the docker commands , understand the networking part of it
   d) Understand the difference between PC's port and container's port
   e) Create a basic hello-world docker file , build an image out of it and run it as a container. Create an account in docker hub and try to push your image.
   f) Check the container status, exec into it and check whats happening inside
   g) Docker Volumes,

5. Kubernetes ( Container Orchestration )
   a) Understand the differences between Docker and Kubernetes
   b) Learn and Understand the Pods, Services,Replicasets, Deployments which are basics of Kubernetes
   c) Try deploying a basic nginx pod using imperative commands by running Kubernetes via Minikube, K3s, Kind etc.
   d) Create a yaml file and deploy a deployment with multiple replicas
   e) Create a service file and expose it via ClusterIP or NodePort service type

6. CICD
   a) Understand the importance of CICD, learn the different stages out of it
   b) Choose one tool and start writing a basic pipeline
   c) Try running the pipeline and check the status of it

   The reason why I chose CICD after Docker and Kubernetes because that can be implemented in the CICD part. If you know the implementation part of Docker and Kubernetes, the automation can be included in CICD part.

7. Terraform ( IAC)

   a) Understand what is IAC and how it helps in maintaining the infra via code
   b) Understand the terraform lifecycle and learn the commands
   c) Try deploying a basic VM of any cloud using terraform
   d) Cleanup the resources after implementing
