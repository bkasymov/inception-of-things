# Inception-of-Things

21 school project

Description
This project aims to introduce you to kubernetes from a developer perspective. You will have to set up small clusters and discover the mechanics of continuous integration. At the end of this project you will be able to have a working cluster in docker and have a usable continuous integration for your applications.

# Keywords

- System administration

# Skills

- Rigor
- Network & system administration

# P1


![Image alt](https://github.com/behaqos/inception-of-things/raw/master/images/p1.png)

<img src="https://github.com/behaqos/inception-of-things/raw/master/images/p1.png", width="10">

At fist exercise create 2 virtual machines (image CentOS, version 7) via vagrant with static IP address and name. After launch script install lite version of kubernetes - K3D. Next step is set agent virtual machine like a node for server virtual machine and check status.

# P2

![Image alt](https://github.com/behaqos/inception-of-things/raw/master/images/p2-2.png)


At the second exercise create one virtual machine and install K3S. In K3S cluster install 3 deployments of web, where second deployment have 3 replicas. Host should have access to all web servers via localhost. 

![Image alt](https://github.com/behaqos/inception-of-things/raw/master/images/p2.png)

# P3

![Image alt](https://github.com/behaqos/inception-of-things/raw/master/images/p3-2.png)

Install K3D where have deployment of ARGO CD. Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. At this task we set configurations for deployment of our simple application and support update of versions via hash compare of commits.


![Image alt](https://github.com/behaqos/inception-of-things/raw/master/images/p3.png)

# Bonus exercise

Install K3D, Argo CD and GitLab service. After that we create new repository and configure for connection between Argo CD and Gitlab for sync and deployment.

# Difference K3D & K3S
1. K3D deploy to Docker-based k3s Kubernetes, and K3S on virtual-machine-based Kubernetes cluster
2. K3D have scalable version
3. More features
4. You could k3D even in little devices (RaspBerry Pi, IoT).
