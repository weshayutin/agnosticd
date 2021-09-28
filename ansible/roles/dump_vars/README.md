dump_vars
=========

Dump all the variables in a human readable way out to a file

Requirements
------------

None, default ansible

Role Variables
--------------

step: a prefix for the log file name

Example Playbook
----------------

* when including it from another role

- import_role: name=dump_vars
  delegate_to: localhost

* when including from a playbook

- import_playbook: dump_vars.yml
  vars:
    step: step002

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
