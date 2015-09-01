# Database MariaDB 10.0

Ansible Role for install and configure the MariaDB 10.0

.. code-block:: yaml

    - name: Database MariaDB 10.0
      hosts: "{{ host_group|default('hosts') }}"
      max_fail_percentage: 20
      user: root
      roles:
        - { role: "database-mariadb10", tags: [ "database" ] }

Authors and License
-------

Written by:
* George Li | [e-Mail](GeorgeL1357@gmail.com) | [GitHub](https://github.com/GeorgeL1)

Licensed under the Apache License, Version 2.0 (the "License");

Copyright 2015, George Li from [Yongxin Solutions](www.yongxin.info)
