# playbook-creator
Ansible playbooks 


# Install  on ubuntu
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible

```

# Now you can install your local playbook:

```
ansible-playbook  -i inventory/hosts   myproject.yml
```
# create file myproject.yml and edit file yml :
```
- hosts: localhost
#or
#- hosts: myserver

  roles: 
      - myproject
```

  # file hosts:
  ```
  [myserver]
  ip 1 remot ssh
  ip 2 rempt ssh
```
 
