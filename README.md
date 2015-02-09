Playbooks
=========

The ansible playbooks that I use.

Install the Last Version of Ansible
-----------------------------------

```bash
sudo git clone git://github.com/ansible/ansible.git --recursive /usr/local/ansible
source /usr/local/ansible/hacking/env-setup
```

OR

```bash
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

Run
---

### workstation
```bash
ansible-playbook workstation.yml --ask-sudo-pass
```
