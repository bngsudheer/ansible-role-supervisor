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


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - hosts: testnode
    user: root
    roles:
        - { role: bngsudheer.supervisor, unix_http_server_usernane: myadminusername, unix_http_server_password: mypassword}
   
    - hosts: servers
      roles:
         - { role: bngsudheer.supervisor }

License
-------

BSD

Author Information
------------------

Sudheer Satyanarayana.
https://github.com/bngsudheer
https://www.techcnorus.net
https://www.gavika.com
