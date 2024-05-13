# LABORATORIO ANSIBLE

Ping al servidor
```
ansible all -m ping -i inventory.yaml -u ubuntu --private-key ~/.ssh/borispacex-key-pair.pem
```
Ejecutar ansible
```
ansible-playbook playbook.yaml -i inventory.yaml -u ubuntu --private-key ~/.ssh/borispacex-key-pair.pem
```