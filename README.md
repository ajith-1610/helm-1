# helm-1
practice

# Search for nginx charts in configured Helm repositories
helm search repo | grep -i nginx

# Check Helm version
helm version

# List all installed releases
helm list

# Show default values for the Bitnami nginx chart
helm show values bitnami/nginx

# Generate Kubernetes manifest files locally using Helm
helm template my-nginx bitnami/nginx

# Install or upgrade the nginx release with NodePort service type
helm upgrade my-nginx bitnami/nginx --set service.type=NodePort

# Check the status of the nginx release
helm status my-nginx
