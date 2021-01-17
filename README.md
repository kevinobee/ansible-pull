# ansible-pull

A run-once script can be pulled and executed on Linux with the following two commands:

```sh
# Install Ansible
sudo apt install -y ansible

# Run the local.yml playbook from a Git repository
sudo ansible-pull -U https://github.com/kevinobee/ansible-pull.git
```
