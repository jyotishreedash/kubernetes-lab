# kubernetes-lab
- [ ] To find how many nodes are running on the cluster - kubectl get nodes
- [ ] Flavor and version of os -Kubectl get nodes -o wide
- [ ] To check cluster - kubectl get nodes
- [ ] Pods running in the system - kubectl get pods
- [ ] To create nginx image -  kubectl run nginx --image=nginx --restart=Never
- [ ] pod/nginx created
- [ ] Control plane is the api server
- [ ] Taints - prevents the scheduling of nodes in the node group
- [ ] Control plane to node-
- [ ] To find the number of deployments - kubectl get deployments
- [ ] Create the Deployment - kubectl create deployment(don’t overlap selectors and labels)
- [ ] To check whether it’s created - kubectl get deployment
- [ ] To see the Deployment rollout status - kubectl rollout status deployment/nginx deployment 
- [ ] To edit the deployment = kubectl edit deployment/name 
- [ ] In API version apps/v1, a Deployment's label selector is immutable after it gets created.

- [ ] Replica sets = A ReplicaSet ensures that a specified number of pod replicas are running at any given time.
- [ ] To delete replica sets = kubectl delete
- [ ] Pods on nodes with more replicas come before pods on nodes with fewer replicas.
- [ ] To find the endpoints = kubectl get endpoint


Pod — smallest unit of Kubernetes
	   abstraction over container
Service — permanent ip address 
Configmap — external configuration of an app
Etcd is the cluster brain (
* To get replica sets on -kubectl get replicas

To find the image of the pod - kubectl describe pod new-replica-set-f6g4n



Create a ReplicaSet using the replicaset-definition-1.yaml file located at /root/.

There is an issue with the file, so try to fix it.            

Pod template
Pod selector



 Kubernetes Component Flow

 Client (kubectl)
     ↓
API Server
     ↓
Scheduler
     ↓
Controller Manager
     ↓
Where to place Pods

 
	    
