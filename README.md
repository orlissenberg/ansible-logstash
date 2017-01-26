Ansible Logstash
================

Install Logstash

Requirements
------------

https://www.elastic.co/guide/en/logstash/current/input-plugins.html

...

Role Variables
--------------

    logstash_user: "root"
    logstash_group: "root"
    logstash_conf_dest: /etc/logstash/conf.d
    
MySQL Slow Query Logs settings.
    
    logstash_mysql_slow_install: false
    logstash_mysql_slow_path: ""

Dependencies
------------

...

Example Playbook
----------------

    ---
    - hosts: webservers
      gather_facts: yes
    
      roles:
        - ansible-logstash

License
-------

MIT

Author Information
------------------

Enjoy.
