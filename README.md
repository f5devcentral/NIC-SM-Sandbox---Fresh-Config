# NIC-SM-Sandbox---Fresh-Config

This step-by-step is for installing and configuring multi-node K8s v1.22.1 with NGINX Service Mesh v1.4.1 and NGINX Plus Ingress Controller v2.2.2

The entire environment will run on a single VM running locally on your MAC/PC and assumes you have enough Bare metal resources to accomodate a VM with 4 cores and ~12GB RAM for best performance. 

By using a free multipass Ubuntu VM and Minikube we can all start with a common operating environment and have fun working with the tools rather than troubleshooting OS environment variables. 

This guide was developed and tested on Macbook only. If you are on a PC, YMMV. 

Start by copying or opening Instructions.txt into Vscode (or your fav txt editor) so you get nice colorized txt formatting. 
