ftp
====

Disables ftp server (vsftpd) service. It's installed though due a security tool
failing if it's not installed. Package should be removed totally for better
security once there is better security tool.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

- name: basic initialization playbook for host
  hosts: all
  tasks:

    - include_role:
        name: ftp

License
-------

BSD

Author Information
------------------

itengval@redhat.com
