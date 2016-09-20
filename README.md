Ansible role: proxyconf
=========

Role setup http proxy configuration on host

Requirements
------------


Role Variables
--------------

Available variables are listed below, along with default values:

* use_proxy: (true or false, default: false)
* proxy: 
* no_proxy: (default: 127.0.0.1,localhost)

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: proxyconf, tags ["proxyconf"]  }

License
-------

BSD

Author Information
------------------
Dirk Hessenmüller

