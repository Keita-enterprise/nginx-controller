
# Author: Ibrehima DevOps Engineeer 
# Install Nginx - Controller 
    helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
    helm repo update
    helm install [RELEASE_NAME] ingress-nginx/ingress-nginx
