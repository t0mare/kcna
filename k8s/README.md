
Exposing application
kubectl port-forward deployment/sinatra 8080:4567 --address 0.0.0.0

Service Nodeport
minikube service <servicename> --url

https://minikube.sigs.k8s.io/docs/handbook/accessing/

Expose (service one liner)
kubectl expose deployment sinatra --port 8080 --target-port 4567
