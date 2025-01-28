# nginx-Ingress-controller-with-ingress

# If you don't have Helm

```bash
kubectl apply -f mtlb.yaml
```
```bash
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.12.0/deploy/static/provider/cloud/deploy.yaml
```
```bash
kubectl get pods --namespace=ingress-nginx
```
```bash
kubectl create deployment demo --image=httpd --port=80
```
```bash
kubectl expose deployment demo --type=NodePort --port=80
```
```bash
kubectl get ingress
```
Ingress external ip put in the vi hosts file and domain name also
```bash
vi /etc/hosts
```
```bash
kubectl edit ingress <name of ingress>
```
