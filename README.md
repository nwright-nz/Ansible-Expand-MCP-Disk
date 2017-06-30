Role Name
=========

Expand disk for Linux (Centos) for Dimension Data Managed Cloud Platform instances.

Requirements
------------

None.

Role Variables
--------------

None. This role assumes (yeah, yeah I know) that you are extending the disk on SCSI 0. This is a once-off, after the provisioning of the server expand.

Dependencies
------------

None

Example Playbook
----------------

Use the role like so:


```yaml
    - hosts: servers
      roles:
         - { role: nwright-nz.expanddisk }
```

License
-------

BSD

Author Information
------------------
  
Nigel Wright  
nigel.wright@dimensiondata.com   
@nigelwright_nz  


