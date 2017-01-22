Role Name
=========

Install and configure Supervisor on CentOS.

Requirements
------------


Role Variables
--------------
Default variables:
  - unix_http_server_usernane: admin
  - unix_http_server_password: secret


Dependencies
------------
 None

Example Playbook
----------------

```yaml
  - hosts: testnode
    user: root
    roles:
        - { role: bngsudheer.supervisor, unix_http_server_usernane: myadminusername, unix_http_server_password: mypassword}
```

License
-------

BSD

Author Information
------------------

Sudheer Satyanarayana.
https://github.com/bngsudheer
https://www.techcnorus.net
https://www.gavika.com
