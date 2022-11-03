# K8S_project

# In this project I created a simple API that shows the different names of the Pod that is responding my request using LoadBalancer service.
# Additionally added another endpoit /enginx that fetches the respose from http://nginx and displays it on the screen.
# Connecting both deployments together, as it is often requestet to connect frontend and backend.
# By simply accessing the pod by its name I am now able to get my root response and the nginx endpoint response.

# kubectl exec k8s-web-to-nginx-5d5584b6cb-mw294 -- nslookup nginx
# kubectl exec k8s-web-to-nginx-5d5584b6cb-mw294 -- wget -qO- http://nginx

# This project is build by using the freeCodeCamp - Kubernetes Course - instructions.
