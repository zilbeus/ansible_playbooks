# ansible_playbooks

### Running playbooks
To run any of the playbooks, pass in the hosts file and extra variables (e.g. the package manager in use).
Use the `-K` flag for playbooks that need admin privileges. Example usage on Fedora with the DNF package manager:
```bash
ansible-playbook -i hosts dirs.yaml --extra-vars "package_manager=dnf" -K
```
