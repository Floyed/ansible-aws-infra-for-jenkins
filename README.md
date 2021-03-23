Setup Jenkins on AWS with infrastructure using Ansible

# Steps

## Copy var_sample.yaml to vars.yaml
## Run following: 

`` ansible-playbook setup-infra.yaml -vvv ``

`` ansible-playbook start-docker-jenkins-container.yaml -vvv ``

`` ansible-playbook teardown-infra.yaml -vvv; ``
