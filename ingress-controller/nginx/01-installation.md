# Install Nginx Ingress Controller on GCP

## Step 1: Deploy the below manifest
```bash
gcloud container clusters get-credentials CLUSTER_NAME --zone ZONE --project PROJECT_ID
```
## Step2:
```bash
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.1/deploy/static/provider/cloud/deploy.yaml
```

FOR AWS:
```bash
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.1/deploy/static/provider/aws/deploy.yaml
```
