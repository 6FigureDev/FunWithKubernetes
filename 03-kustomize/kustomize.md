# Check for For Valid Config
```
kubectl apply -k deployment --dry-ruy
```
# Check Config Against Current Deployed State
```
kubectl apply -k deployment --server-dry-ruy
```
# Generate Kubernetes Manifest
```
kubectl kustomize deployment
```
# Apply Deployment Config 
```
kubectl apply -k deployment
```

# Apply Job Config 
```
kubectl apply -k Job
```