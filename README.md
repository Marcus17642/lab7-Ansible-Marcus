Marcus Su and Rafeel Geelani

# Create ssh key
ssh-keygen -t ed25519 -f ~/.ssh/aws

# check the syntax of the playbook

ansible-lint playbook.yml

# run the playbook

ansible-playbook playbook.yml

[lab7.png]
