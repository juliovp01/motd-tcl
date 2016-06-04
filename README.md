Ansible Satellite 6 Install
===========================

Role to install and do configure motd-tcl. This role is based on work found at: http://www.mewbies.com/how_to_customize_your_console_login_message_tutorial.htm

Requirements
------------

You will need ansible and tcl to run this. All required packages are installed.

Role Variables
--------------

No variables are required for this playbook


Dependencies
------------

There is no role dependency for this role.

Host File
----------

The host file for this role is hosts.target and the format is: 

[target]
IPs FOR LINUX SERVER

How to run the playbook
------------------------

** Run the playbook

ansible-playbook -i hosts.target motd.yaml


License
-------

MIT

Author Information
------------------

Julio Villarreal Pelegrino <julio@linux.com> more at: http://wwww.juliovillarreal.com