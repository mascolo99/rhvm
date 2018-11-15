#
# Playbook para configurar vms en Ovirt
#
# comando: ansible-playbook --verbose ovirt.yml
# Autor: Sebastian Mascolo
#
- hosts: localhost
  vars:
    ansible_python_interpreter: /usr/bin/python2

  roles:
    - ovirt
