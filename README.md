Role Name
=========

This role will install the most recent, official release of go by default or it will optionally install another version (as defined by the variable go_version)

Requirements
------------

None

Role Variables
--------------

go_version, the version of go to download and install

Dependencies
------------


Example Playbook
----------------

	---
	- hosts: 127.0.0.1

	roles:
	  - ansible-go

License
-------

BSD

Author Information
------------------

Edwin Skidmore (edwin@cyverse.org)
