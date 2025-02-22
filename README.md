Marcus Su and Rafeel Geelani

# Create ssh key
ssh-keygen -t ed25519 -f ~/.ssh/aws

# import key

./import_lab_key ~/.ssh/aws.pub

# copy ssh
# check the syntax of the playbook

ansible-lint playbook.yml

# run the playbook

ansible-playbook playbook.yml


![alt text](lab7.png)
