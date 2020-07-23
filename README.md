# Microk8s

The smallest, simplest, pure production K8s.
For clusters, laptops, IoT and Edge, on Intel and ARM.

--------------------------------------------------------------------------------

## Start Vagrant

```
vagrant up
```

If you would like to enable services. edit at `install-microk8s.sh`

```
microk8s.enable dashboard
microk8s.enable dns
microk8s.enable fluentd
microk8s.enable ingress
microk8s.enable istio
microk8s.enable jaeger
microk8s.enable metrics-server
microk8s.enable prometheus
microk8s.enable registry
microk8s.enable linkerd
microk8s.enable storage
```
