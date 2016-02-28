A Basic Ansible Template for Projects
=====================================

This is a basic template for adding [Ansible](https://ansible.com) integration to a project.

Best Practices
--------------

Ansible documentation on best practices for directory layout, playbooks, roles, inventories, and variables.

[http://docs.ansible.com/ansible/playbooks\_best\_practices.html]()

Layout
------

    main.yml

    group_vars/
        all/
            vars.yml
        role-1/
            vars/yml

    inventories/
        development
        production

    roles/
        role-1/
            handlers/
                handlers.yml
            tasks/
                main.yml

Author
------

Peter Schaadt

[https://github.com/peterfschaadt]()

[http://peterschaadt.com]()
