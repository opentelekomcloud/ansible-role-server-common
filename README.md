OpenTelekomCloud Server-Common role
===================================

A quick role to apply most obvious initial setting to any cloud server. Currently following is done:

- Root login disabled
- Disable password login
- Limit Journalctl disk usage to avoid disk overflow
- Install often required packages

Requirements
------------

None.

Role Variables
--------------

  journalctl_max_disk_usage:1G - Maximal disk usage by Journalctl


Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: bastion
      roles:
         - otc_server_common

License
-------

Apache


Author Information
------------------

OpenTelekomCloud
