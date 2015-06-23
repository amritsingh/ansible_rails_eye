Role Name
========

Ansible role to load config for eye and to restart all the jobs

Requirements
------------

Should have installed 'eye' gem.

Role Variables
--------------

In the current version, you can specify the following variables:

- rails_deploy_user
- rails_deploy_app_name
- rails_env
- eye_force_restart
- ruby_version
- gemset
- eye_config_path
- rails_deploy_shell_prefix

Note: There are no default values for the above mentioned variables.

Dependencies
------------

This package has no dependencies on modules not included with Ansible by default.

License
-------

MIT

Author Information
------------------

Created by Amrit Singh
https://www.twitter.com/_amrit_

