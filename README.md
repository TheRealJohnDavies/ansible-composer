Ansible Role: Composer
=========

This is an Ansible role for installing/updating Composer, the depependency manager for PHP.

Requirements
------------

PHP

Role Variables
--------------

| Variable | Description | Default |
|----------|-------------|---------|
| php_executable | Path to your PHP executable | php |
| composer_version| Version of Composer to install | 1.6.4 |
| composer_install_dir | Directory to install Composer | /usr/local/bin |

Dependencies
------------

None.

Example Playbook
----------------

Example of how to use this role:

    - hosts: webservers
      roles:
        - { role: TheRealJohnDavies.composer, php_executable: /usr/local/bin/php }

License
-------

MIT

Author Information
------------------

TheRealJohnDavies

