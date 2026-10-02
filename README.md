# My First Ansible Project

Ansible se Linux server configure kiya.

**Kya kiya:**
1. `appuser` naam ka user banaya
2. `/opt/myapp` folder banaya aur owner appuser ko diya

**Command:**
ansible-playbook -i inventory.ini main.yml --ask-become-pass

**Result:** ok=3 failed=0
