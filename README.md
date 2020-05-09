Playbook for launch instance AWS
1)key pair - chmod 400
2)/etc/ansible/ansible.conf - host_key_checking = false
3)/etc/ansible/hosts :
[ec2hosts]
[ec2hosts:vars]
ansible_ssh_user=ubuntu
ansible_ssh_private_key_file=/root/.ssh/**-***.pem
