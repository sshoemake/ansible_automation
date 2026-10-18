# Ansible Repository

ansible-playbook --ask-become-pass site.yml

## List Tags

ansible-playbook --list-tags site.yml

## Install the collection using ansible-galaxy

ansible-galaxy collection install -r collections/requirements.yml

ansible-playbook --ask-become-pass update-os.yml
ansible-playbook --ask-become-pass hardening-os-ssh.yml
ansible-playbook --ask-become-pass install-docker.yml
ansible-playbook --ask-become-pass install-portainer.yml

ansible-playbook -i 192.168.0.121, --ask-become-pass install-docker.yml