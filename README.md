Ansible playbooks to Launch and Terminate EC2 instances in AWS cloud


aws-ec2-deletion.yml --> Playbook Execution for the playbook to delete multiple Ec2 Instances at a time

ansible-playbook aws-ec2-deletion.yml --extra-vars='{"instance_ids": [i-xxxxx,i-xxxx,i-xxxx]}' -vvv
