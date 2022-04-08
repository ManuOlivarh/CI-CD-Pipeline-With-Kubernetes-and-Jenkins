# CI-CD-Pipeline-With-Kubernetes-and-Jenkins

This is a tutorial for creating a jenkins pipeline with docker and kubernetes.

## Prerequisites

- Kubernetes Cluster


## Install Jenkins

a) Install Java

```sh
sudo apt update
sudo apt install openjdk-8-jdk
```

b) Add Jenkins Repository & append package repository address to the server’s source.list

```sh
wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
```
c) Install Jenkins

```sh
sudo apt update
sudo apt install jenkins
```


---- TUTORIAL IN DEVELOPMENT
