
# Wordpress & MariaDB on K8S

[strong]Wordpress & MariaDB Deployment on K8S using Manifests[strong]

A simple tutorial to deploy Wordpress & MariaDB on kubernetes using manifests only

## Create a namespace

```sh
kubectl create ns wordpress
```

## Apply all manifests to this namespace

```sh
kubectl apply -f . -n wordpress
```

## Delete all resources

```sh
kubectl delete -f . -n wordpress
```

## Delete also namespace

```sh
kubectl delete ns wordpress
```
