# ansible-rhel-hardening
Ansible playbooks for RHEL/Rocky Linux security hardening (CIS/DISA STIG aligned).

## Usage
```bash
# Full hardening
ansible-playbook -i inventory/hosts playbooks/harden.yml

# Audit only (no changes)
ansible-playbook -i inventory/hosts playbooks/audit.yml

# Specific role
ansible-playbook -i inventory/hosts playbooks/harden.yml --tags ssh
```
