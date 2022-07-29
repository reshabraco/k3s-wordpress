# install k3s on OS Ubuntu
```bash
sudo apt update
```
```bash
sudo apt upgrade ca-certificates --yes
```
```bash
curl -sfL https://get.k3s.io | sh -
```
```bash
sudo k3s kubectl get node
```
```bash
sudo chmod 644 /etc/rancher/k3s/k3s.yaml
```
```bash
wget https://github.com/reshabraco/k3s-wordpress.git
cd k3s-wordpress
```
```bash
kubectl apply -k ./
```
```bash
kubectl get pods -o wide
```
```bash
kubectl get svc
```

