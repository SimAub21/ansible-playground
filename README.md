# Ansible Playbooks for the home network

## Execute Playbook

```bash
ansible-playbook -i inventory.ini playbook-name.yaml
```

### VPS first time:

```bash
ansible-playbook -i inventory.ini debian/secure_vps.yaml -u root -e "ansible_port=22" -k -K
```