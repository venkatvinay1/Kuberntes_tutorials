# Kuberntes Tutorials

## Commands used in kubernetes

### Interacting with Pods

-- kubectl get nodes 

-- kubectl get pod podname

-- kubectl describe pod podname
 
-- kubectl get pod -o wide 
 
-- kubectl get pod podname -o yaml > pod-specs.yaml
 
-- nano pod-specs.yaml

-- kubectl run nginx --image=nginx:latest

-- kubectl get -h

-- kubectl run nginx --image=nginx --dry-run=client -o yaml > pods.yaml

-- kubectl apply -f pods.yaml

### Interacting with ConfigMaps

-- kubectl get configmap

-- kubectl delete configmap name_of_configmap

-- kubectl 
