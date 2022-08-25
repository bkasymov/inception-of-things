# Inception-of-Things

21 school project

Description
This project aims to introduce you to kubernetes from a developer perspective. You will have to set up small clusters and discover the mechanics of continuous integration. At the end of this project you will be able to have a working cluster in docker and have a usable continuous integration for your applications.

# Keywords

- System administration

# Skills

- Rigor
- Network & system administration

# P3
# Difference K3D & K3S
1. K3D deploy to Docker-based k3s Kubernetes, and K3S on virtual-machine-based Kubernetes cluster
2. K3D have scalable version
3. More features
4. You could k3D even in little devices (RaspBerry Pi, IoT).


# Useful commands:


# TODO проверить красные линии и 
vagrant up
kubectl get all -n kube-system
kubectl get all 
kubectl get nodes -o wide
kubectl get pods --all-namespaces
kubectl get ns
kubectl get deploy
ifconfig eth1 | grep inet
curl -H "Host:app1.com" 192.168.57.110 | grep LOCAL
kubectl get svc