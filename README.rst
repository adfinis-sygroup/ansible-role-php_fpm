============
ROLE PHP_FPM
============

.. image:: https://img.shields.io/github/license/adfinis-sygroup/ansible-role-php_fpm.svg?style=flat-square
  :target: https://github.com/adfinis-sygroup/ansible-role-php_fpm/blob/master/LICENSE

.. image:: https://img.shields.io/travis/adfinis-sygroup/ansible-role-php_fpm.svg?style=flat-square
  :target: https://travis-ci.org/adfinis-sygroup/ansible-role-php_fpm

.. image:: https://img.shields.io/badge/galaxy-adfinis--sygroup.php_fpm-660198.svg?style=flat-square
  :target: https://galaxy.ansible.com/adfinis-sygroup/php_fpm

This role is used to install and configure php-fpm from the SCL repositories.


Requirements
=============

This role has no requirements.


Role Variables
===============

Currently, everything in this role is hardcoded.


Dependencies
=============

This role has no dependencies.


Example Playbook
=================

.. code-block:: yaml

  - hosts: servers
    roles:
       - { role: adfinis-sygroup.php_fpm }


License
========

`GPL-3.0 <https://github.com/adfinis-sygroup/ansible-role-php_fpm/blob/master/LICENSE>`_


Author Information
===================

php_fpm role was written by:

* Adfinis SyGroup AG | `Website <https://www.adfinis-sygroup.ch/>`_ | `Twitter <https://twitter.com/adfinissygroup>`_ | `GitHub <https://github.com/adfinis-sygroup>`_

