Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

# these are examples
# token can be generated in influxdb2 and then copied here
# 
influx_telegraf_urls: ["http://myinfluxdb.mydomain:8086"]  
influx_telegraf_organzation: "org01"
influx_telegraf_bucket: "telegraf"
influx_telegraf_token: xNW1Gn2lIacmHlSjFxsOe2NeGLgPYwBkzkghNfcK7hxAUEk72qp6gF98akXUgwYhnPn-mePpeKVFdd_NZ_CNHA==


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: hosts_with_cool_telegraf_agent
      roles:
         - role: arikkert.telegraf

License
-------

BSD

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT

