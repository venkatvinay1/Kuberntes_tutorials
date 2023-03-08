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

-- kubectl create configmap vinay --from-literal=user=vinayvenkat --from-literal=pwd=1234 (from literal)

-- kubectl describe configmap vinay

-- touch user.txt

-- nanao user.txt

-- touch pass.txt

-- nano pass.txt

-- kubectl create configmap hello --from-file=user.txt --from-file=pass.txt (from a file)

-- kubectl apply -f cm.yaml (from a yaml file)











