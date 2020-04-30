-- This creates the job
kubectl create job hello-world --image=hello-world

-- This creates the deployment 
kubectl create deploy hello-world --image=hello-world

-- This creates the deployment and saves the manifest in a file
kubectl create deployment hello-there --image=hello-world -o=yaml > k8s_deploy_manifest.yml

-- This allowed the deployment to be updated
kubectl apply -f ./k8s_deploy_manifest.yml