# LABORATORIO ANSIBLE

ansible all -m ping -i inventory.yaml -u ubuntu --private-key ~/.ssh/borispacex-key-pair.pem

ansible-playbook playbook.yaml -i inventory.yaml -u ubuntu --private-key ~/.ssh/borispacex-key-pair.pem