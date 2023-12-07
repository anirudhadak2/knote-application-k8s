# knote-application-k8s


##parksmap application on k8s

 kubectl create deploy mydep --image quay.io/openshiftroadshow/parksmap 
    
kubectl create deploy mydep1 --image quay.io/openshiftroadshow/parksmap  --dry-run=server -o yaml > dep.yml 
    
 kubectl expose deploy mydep --port=8080 --type=NodePort 
    
 kubectl get svc
 
 
