[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-namd/workflows/CI/badge.svg)](https://github.com/grycap/ansible-role-namd/actions?query=workflow%3ACI)

NAMD Role
=======================

This ansible role installs [NAMD](http://www.ks.uiuc.edu/Research/namd/). A parallel, object-oriented molecular dynamics code designed for high-performance simulation of large biomolecular systems.

Role Variables
----------------

The variables that can be passed to this role and a brief description about them are as follows.

	# Application install path
	install_path: /opt

Example Playbook
----------------

This an example of how to install this role:

    - hosts: server
      roles:
      - { role: 'grycap.namd' }

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled.
If you want to contribute, you have to create a branch, upload your changes and then create a pull request.
Thanks
