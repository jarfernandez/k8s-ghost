# k8s-ghost
[Ghost](https://ghost.org/es/) en [Kubernetes](https://kubernetes.io/).

Para arrancar Ghost, ejecutar los siguientes comandos:
```
$ kubectl create -f ghost-persistent-volume-claim.yaml 
$ kubectl create -f ghost-persistent-volume.yaml 
$ kubectl create -f ghost-deployment.yaml
$ kubectl create -f ghost-service.yaml
```

Para acceder a Ghost, ejecutar el siguiente comando:
```
$ minikube service ghost-service
```

---

Tags: devops, ghost, k8s, kubernetes