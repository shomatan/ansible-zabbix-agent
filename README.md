Ansible Role: Zabbix agent
=========

Installs zabbix-agent.

Requirements
------------

None.

Role Variables
--------------

    zabbix_agent_version: "3.2"
    zabbix_agent_server_host: 127.0.0.1
    zabbix_agent_ListenPort: 10050
    zabbix_agent_ListenIP: 0.0.0.0
    zabbix_agent_Hostname: "{{ ansible_fqdn }}"

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.zabbix-agent }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno