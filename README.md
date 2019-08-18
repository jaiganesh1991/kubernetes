# kubernetes
This repo contains demo documents for Kubernetes

Created the deployment.yaml file. Describes the way the image and port that needs to be described for the deployment

Created the service.yaml file to describe the service and the static IP address to use. This exposes the service to the outside world.


Commands section:
kubectl create -f deployment.yaml or kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
