# helm-1
practice

commands:
> helm search repo | grep -i nginx
> helm version
> helm list
> helm show values bitnami/nginx
> helm template my-nginx bitnami/nginx
> helm upgrade my-nginx bitnami/nginx --set service.type=NodePort
> helm status my-nginx
