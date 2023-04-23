
# Wordpress & MariaDB Deployment on Kubernetes with Manifests

This is a simple tutorial to deploy Wordpress & MariaDB on kubernetes using manifests only

## Create a namespace

```sh
kubectl create ns wordpress
```

## Apply all manifests to this namespace

```sh
kubectl apply -f . -n wordpress
```
