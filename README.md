# week_11_lab

Run Ec2 Instances for ansible
```bash
cd terraform
terraform init
terraform validate
terraform plan
terraform apply
```

Apply Ansible configuration
```bash
ansible-playbook playbook.yml
```

Note:
Change terraform ```main.tf``` under ```key_name``` to a key pair in was

Once finished, destroy the ec2 instance
```bash
terraform destroy
```
