Ansible Role: Firewall
=========

Эта роль управляет настройками службы firewalld/ufw в ОС Linux.

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены ниже вместе со значениями по умолчанию в файле **defaults/main.yml**.
Включение/отключение Firewall задается переменной `firewall_enable`, по умолчанию служба включена `true`.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - firewall

License
-------

BSD

Author Information
------------------

Chubik Sergey.
