# Projet SMB111

## Objectifs 
- Configuration hardening de 3 VM
- Mise en place automatisé d'un cluster k8s avec 1 node sur chaque VM
- Mise en place automatisé de longhorn et argocd
- Deploiment du service via argocd  


## Hardening
Les services gérés sont : 
- sshd
- iptables
- repo / packages
- users / permissions


## K8S
Mise en place d'un node 
Mise en place de rancher pour une meilleur visualisation
Mise en place de longhorn pour gestion du volume persistent entre les 3 nodes
Mise en place d'un repo gitops dans le path /iaplateform du repo 
