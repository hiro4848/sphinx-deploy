ajgarlag.kibana4
================

Ansible role to install Kibana4.

[![Build Status](https://travis-ci.org/ajgarlag/ansible-kibana4.svg?branch=master)](https://travis-ci.org/ajgarlag/ansible-kibana4)

Role Variables
--------------

* **ajgarlag_kibana4_version**: Version of kibana4 to install (defaults to `4.0.2`)
* **ajgarlag_kibana4_settings**: Dict of parameters to write into the kibana4 config file (defaults to `{}`).


Example Playbook
----------------

```yml
- hosts: all
  roles:
    - role: ajgarlag.kibana4
      ajgarlag_kibana4_settings:
        "elasticsearch_url": "http://127.0.0.1:9200"
```


License
-------

MIT

Author Information
------------------

Developed with ♥ by [Antonio J. García Lagar](http://aj.garcialagar.es).
