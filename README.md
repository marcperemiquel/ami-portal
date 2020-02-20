## Portal AMI

This AMI Builder, creates a new Agora Portal AMI out of the latest Amazon Ubuntu AMI.

## Source code structure

```bash
├── roles                              <-- Roles to be used
│    └── requirements.yml              <-- Ansible galaxy file with roles to import
├── sic
│    └── aca.yml                       <-- Main configuration SIC
├── ansible-playbook.yml               <-- Portal ansible playbook file
├── ansible.cfg                        <-- Specific ansible config
├── aws-portal.yml                     <-- Portal packer configuration file
├── ...                         	   <-- ...
└── README.md
```
