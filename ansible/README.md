***ANSIBLE README***

To run the playbook_docker.yml, execute the bellow command:
```
ansible-playbook playbook_docker.yml
```

To run the ansible playbook with encrypted docker credentials and push the image to Docker Hub, execute:
```
ansible-playbook --ask-vault-pass playbook_docker.yml
```