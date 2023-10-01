# k8smongoexpress
<p>

  <img width="400" alt="Capture" src="https://github.com/FrancisNtahimpera/k8smongoexpress/assets/27433619/b3be6acd-3e33-4f53-bb39-e8e15e765e56">
  <img width="400" alt="Capture3" src="https://github.com/FrancisNtahimpera/k8smongoexpress/assets/27433619/154ab230-4083-4ec0-8b7d-b5dbf5ca3922">
<img width="200" alt="Capture2" src="https://github.com/FrancisNtahimpera/k8smongoexpress/assets/27433619/53529cb8-5358-4fa0-bdfe-b720074caef3">

</p>


### kubectl apply commands
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

### give a URL to external service in minikube

    minikube service mongo-express-service
