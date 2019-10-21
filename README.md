# kubernetes-starter
Sample resources for getting started with Kubernetes
## Commands
To create  a new Pod
`kubectl create -f .\pod.yml`

To check Pods status
`kubectl get pods`

To Delete Pods
`kubectl delete pods hello-world`


To Create Replication Controller

`kubectl create -f .\rc.yml`

To update the Replication Controller

`kubectl apply -f .\rc.yml`


To Expose the RC to a Sevice 

 `kubectl expose rc hello-world --name=hello-svc --target-port=8080 --type=NodePort`
 
 To See whats in the Service and check the Node Port
 
 `kubectl describe svc hello-svc`
 
 To Delete the Replication Controller
   
 `kubectl delete rc hello-world`

 


