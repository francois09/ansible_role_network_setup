Network_Setup
=============

Simple role to install and configure network_setup

Requirements
------------

No requirements

Role Variables
--------------

By default the role didn't install network_setup nor configure

```
network_setup__install: False
network_setup__configure: False
network_setup__initial_interface_mtu: In some case, MTU should be modified
network_setup__primary_network_interface: Primary network interface
network_setup__initial_dns: Can be provider DNS, used for initial DNS config, and can be overriden by DNS role
```

Dependencies
------------

None

Example Playbooks
-----------------

License
-------

GPL v3

Author Information
------------------

François TOURDE
