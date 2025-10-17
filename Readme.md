## 1. Start the ingress-controller 
# `kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.10.1/deploy/static/provider/cloud/deploy.yaml`

## 2. Then create internal (ClusterIp) service to expost it for backend , frontend
## 3. kubectl apply -f ingress.yml
## 4. In your DNS provider (e.g., Cloudflare, GoDaddy, Route53):

# Add this record:

# Type	Name	Value	TTL
# CNAME	week-36	LB_IP   AUTO