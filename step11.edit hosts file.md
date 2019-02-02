## minikube or kubeadm

```sh
$ sudo vi /etc/hosts
```

try to get minikube ip:

```sh
$ minikube ip
192.168.99.102
```

add the following line or append to localhost:

```sh
192.168.99.102 localhost rancher.myhost.k8s jenkins.myhost.k8s portainer.myhost.k8s registry.myhost.k8s
```

## dokcer for Mac & Windows with Kubenetes

add the following line or append to localhost:

```sh
127.0.0.1 localhost rancher.myhost.k8s jenkins.myhost.k8s portainer.myhost.k8s registry.myhost.k8s
```