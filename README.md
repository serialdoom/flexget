Role Name
=========

Install flexget and setup the flexget user

Role Variables
--------------

 - `flexget_conf_url`: url that contains the flexget config. Sample flexget config :

```yaml
tasks:
    all_series:
        rss: http://showrss.info/your-url-goes-here
        series:
            - The Walking dead
        download: /tmp
```

Example Playbook
----------------

```yaml
---
 - hosts: all
   roles:
     - flexget
```

License
-------

BSD

