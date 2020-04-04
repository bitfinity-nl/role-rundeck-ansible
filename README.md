# role-rundeck-ansible
This role is designed for configuration management and combines best of both worlds with Rundeck an Ansible-core.

Example Playbook
----------------

This is an example how to use the role:

    - hosts: rundeck-01
      become: yes

      vars:
        
      roles:
        - app-cert-selfsigned
        - role-rundeck-ansible
