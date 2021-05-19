## To install postfix:
ansible-playbook /etc/ansible/playbooks/postfix.yml --tags "init postfix"

## To delete postfix:
ansible-playbook /etc/ansible/playbooks/postfix.yml --tags "drop postfix"
