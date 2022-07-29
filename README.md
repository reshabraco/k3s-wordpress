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


