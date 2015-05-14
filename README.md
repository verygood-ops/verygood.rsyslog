verygood.rsyslog
=========

Installs rsyslog

Role Variables
--------------

- `rsyslog_server_hostname`: 192.168.1.1
- `rsyslog_server_port`: 514
- `rsyslog_server_proto`: tcp
- `rsyslog_forwarding`: no
- `rsyslog_repeated_msg_reduction`: "on"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: verygood.rsyslog, rsyslog_forwarding: no }

    - hosts: clients
      roles:
         - { role: verygood.rsyslog, rsyslog_forwarding: yes }

License
-------

BSD
