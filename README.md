Playbook for launch instance AWS
key pair - chmod 400
/etc/ansible/ansible.conf - host_key_checking = false
etc/ansible/hosts :
[ec2hosts]
[ec2hosts:vars]
ansible_ssh_user=ubuntu
ansible_ssh_private_key_file=/root/.ssh/**-***.pem
