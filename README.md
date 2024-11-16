# devops-programme

To run the playbook_docker.yml, execute the bellow command:
```
ansible-playbook playbook_docker.yml
```

To run the ansible playbook with encrypted docker credentials and push the image to Docker Hub, execute:
```
ansible-playbook --ask-vault-pass playbook_docker.yml
```

To build the docker image, execute:
```
docker build -t bobby84/getting-started-index-html .
```

To list the current images, execute:
```
docker image ls 
```
 
To push the docker image to Docker Hub, execute:
```
docker push bobby84/getting-started-index-html
```

To run the playbook_docker.yml, execute the bellow command:
```
ansible-playbook playbook_docker.yml
```

To run the ansible playbook with encrypted docker credentials and push the image to Docker Hub, execute:
```
ansible-playbook --ask-vault-pass playbook_docker.yml
```

To run ***github_actions_hw.yml*** workflow, any change should be done in the README.md file and should be
commited and pushed to GitHub. Then a PR should be made to the main branch and merged. It will trigger the 
Actions tab in GitHub.
