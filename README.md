# Ansible Playbooks : Kubernetes

# Prérequis

3 VM CentOS 8.x avec :

- UUID différents (uuidgen pour avoir un nouveau UUID puis le mettre dans /etc/.../ifcfg-...)
- Bridge
- user ansible + visudo pour tout lancer en nopasswd
- ssh-keygen et ssh-copy-id du master vers les deux nodes
