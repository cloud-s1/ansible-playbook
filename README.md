### Ansible-playbook-for-Ubuntu-24.04-LTS

ansible-playbook -i github-actions-demo/inventory.ini github-actions-demo/deploy.yml -e "env=dev acr_password=<your_acr_password>" --private-key ~/.ssh/root.pem -u root