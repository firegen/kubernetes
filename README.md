# kubernetes
Home Kubernetes server

## Topology:
DNS server and NGNIX server to forward traffic to kubernetes masterIP
 ### Kubernetes cluster nodes:
 ```
 hostname=kubemaster1, ip=192.168.1.51
 hostname=kubenode1, ip=192.168.1.52
 hostname=kubenode2, ip=192.168.1.53
```
## Nginx settings:
### 1. Install nginx 
```
apt get install nginx
```
### 2. Get certificates from the kubernetes master node.
All certs and private keys could be found at "/etc/kubernetes/pki" 


### 3. Configure all hosts redirection in /etc/nginx/nginx.conf
see file in the repo "nginx.conf"
