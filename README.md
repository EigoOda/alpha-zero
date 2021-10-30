
# Create Kubernete cluster with kubeadm

## Prepare

### Create nodes
https://kubernetes.io/ja/docs/setup/production-environment/tools/kubeadm/install-kubeadm/

### Create Kubernetes cluster using kubeadm
https://kubernetes.io/ja/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/

## Install CNI component

```bash
kubectl apply -f calico.yaml
```

## Install metric-server

```bash
kubectl apply -f metric-server.yaml
```



