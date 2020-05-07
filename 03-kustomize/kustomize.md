# Check for For Valid Config
```
kubectl apply -k deployment --dry-run
```
# Check Config Against Current Deployed State
```
kubectl apply -k deployment --server-dry-run
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