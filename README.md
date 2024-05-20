## kubectl get all
## kubectl get all --all-namespaces
## kubectl get po
## kubectl get po --show-labels
## kubectl get po --show-labels -l release=<release number/version>
## kubectl get po --show-labels -l release=0-5
## kubectl delete po --all
## kubectl describe po <pod name>
## kubectl describe svc <service name>
## kubectl describe rs <replicaSet name>
## kubectl rollout status deployment <deployment name>
## kubectl rollout history deployment <deployment name>
## kubectl rollout undo deployment <deployment name> --to-revision=2

## kubectl get ns
## kubectl get po -n kube-system
## kubectl get all -n kube-system
## kubectl describe svc kube-dns -n kube-system

## kubectl exec -it <pod mane> sh
## cat etc/resolv.conf
## nslookup <service name>

## curl -L github_url.tar.gz > filename.tar.gz
## tar xvf filename.tar.gz (to extract)

## kubectl logs <pod name>
## kubectl logs -f <pod name>

## kubectl edit svc -n <namespace name> <service name>

## kubectl get nodes
## kubectl describe node <node name>

# Mertices
## kubectl top po
## kubectl top node


# HPA
## kubectl autoscale deployment <deployment name> --cpu-percentage 400 --min 1 --max 4
## kubectl get hpa
## kubectl describe hpa <deployment name>
## kubectl describe hpa <deployment name> -o yaml 
## kubectl delete hpa <deployment name> 

# curl in loop
## while true; do curl http://localhost:30080/api; echo; done

## kubectl get configMap 
## kubectl get cm
## kubectl describe cm <configMap name> 
## kubectl 
## kubectl 
## kubectl 
## kubectl 