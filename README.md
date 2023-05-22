Ansible-Role: Metasploit
========================

This role simply installs Metasploit


Requirements
------------

Any Debian or Ubuntu should do.

Role Variables
--------------

```
metasploit_url: "https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb"
```

Example Playbook
----------------

```
    - hosts: localhost
      roles:
         - role: metasploit
```

License
-------

GPL-3.0

Author Information
------------------

Wolfgang Hotwagner (https://www.ait.ac.at)
