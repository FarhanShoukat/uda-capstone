# uda-capstone
Cloud DevOps Engineer Nanodegree Capstone Project

## Cluster Creation
`ekctl` was used to create the kubernetes cluster on AWS EKS.
```bash
eksctl create cluster --name nginxHelloWorld
```

## CircleCI configuration
Following environment variables were set in CircleCI configuration
* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
* AWS_REGION
* AWS_ECR_REGISTRY_ID (The 12 digit account Id.)
