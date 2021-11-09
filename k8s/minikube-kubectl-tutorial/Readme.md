# Kubernetes

In this directory you'll find Kubernetes manifests and configuration files used in our YouTube videos. 

## Minikube and Kubectl

Installation instructions below for our YouTube video can be found here [https://www.youtube.com/watch?v=5fDGNyviXEI](https://www.youtube.com/watch?v=5fDGNyviXEI).

Please see k8s/helloworld-deployment.yml for the manifest deployed in the video.

### Install Minikube
```bash
wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```

### Install Kubectl

## Usage

```bash
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
