#Rendu Packer Mael COUBRUN

#Préparation

Avant de lancer le build, veuillez à bien avoir le service Qemu et Ansible d'installer.
Qemu: ``dnf install '@Virtualization Host' ``
Ansible: ``sudo yum install ansible ``

#Playbook.yml

Le playbook.yaml a besoin d'un template du service qui est dans le dossier template. Le dossier se trouve dans ce chemin (si vous souhaitez le modifier, il faudra cahnger le chemin dans le playbook) :

`` TP1_Bastien/template/golang.service ``

