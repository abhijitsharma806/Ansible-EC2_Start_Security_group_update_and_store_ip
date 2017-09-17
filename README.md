# ec2_start_and_securitygroup_update_store_ip
* This playbook will do the below tasks.
* Start the existing EC2 instance.
* Store the EC2-public IP in a new file. (/etc/ansible/ec2_ips)
* Update the security group with your public corporate IP.
* The port you want to allow in EC2 security group you can add and modify on "tasks/main.yml" file.
* Replace your variable value in "vars/main.yml" file.

- aws_access_key: "A******************"
- aws_secret_key: "Xz***********************************Yv"
- aws_region: "us-east-1"
- vpc_id: "vpc-e4c19d83"
- vpc_subnet_id: "subnet-ace216e3"
- instance_ids1: "i-080b16942367582b3"  
