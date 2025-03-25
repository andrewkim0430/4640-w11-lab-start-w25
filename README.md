# 4640-w11-lab-start-w25

ansible-playbook playbook.yml

roles/
  ├── ubuntu_server/
  │   ├── tasks/
  │   ├── templates/
  │   ├── files/
  │   ├── handlers/
  └── rocky_server/
      ├── tasks/
      ├── templates/
      ├── files/
      ├── handlers/

4640-w11-lab-start-w25/
├── README.md
├── server-img.jpg
├── .gitignore
├── terraform/
│   ├── main.tf
│   ├── provider.tf
│   └── modules/
│       └── web-server/
│           ├── main.tf
│           ├── outputs.tf
│           └── variables.tf
└── ansible/
    ├── ansible.cfg
    ├── playbook.yml
    ├── inventory/
    │   └── aws_ec2.yml
    └── roles/
        ├── ubuntu_server/
        └── rocky_server/

