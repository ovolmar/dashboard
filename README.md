Splunk Enterprise Dashboards
=========

Adds your custom dashboards to Splunk Enterprise


Role Variables
--------------
```
dashboard_dir
splunk_user 
splunk_group

```

Example Playbook
----------------

    - hosts: splunk-enterprise,!universalForwarders
      roles:
         - dashboard

License
-------

BSD

Author Information
------------------
oz volmar [o.volmar@gmail.com )