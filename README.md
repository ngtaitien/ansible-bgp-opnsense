Pre-install:

brew install hudochenkov/sshpass/sshpass

ansible-galaxy collection install git+https://github.com/O-X-L/ansible-opnsense.git

Run: ansible-playbook -i inventory.yml playbook.yml
