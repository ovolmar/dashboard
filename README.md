Splunk Enterprise Health
=========

Monitor changes to Splunk Enterprise Server


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

dashboard_dir
splunk_user 
splunk_group

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: splunk-enterprise
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------
oz volmar [o.volmar@gmail.com )