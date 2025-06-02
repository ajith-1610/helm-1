# helm-1
practice

1. Search for nginx charts in configured Helm repositories
helm search repo | grep -i nginx

2. Check Helm version
helm version

3. List all installed releases
helm list

4. Show default values for the Bitnami nginx chart
helm show values bitnami/nginx

5. Generate Kubernetes manifest files locally using Helm
helm template my-nginx bitnami/nginx

6. Install or upgrade the nginx release with NodePort service type
helm upgrade my-nginx bitnami/nginx --set service.type=NodePort

7. Check the status of the nginx release
helm status my-nginx
