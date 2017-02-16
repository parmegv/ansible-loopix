Role Name
=========

Installs the Loopix mix network into a virtualenv, along with its dependencies.

Requirements
------------

Ansible, tested with 2.1.1.0

Role Variables
--------------

The variables that can be passed to this role are as follows:

	loopix_git_repo: "https://github.com/UCL-InfoSec/loopix.git"
	loopix_dir: "~/loopix" # Loopix gets installed here
	loopix_virtualenv: "~/.virtualenvs/loopix" # Virtualenv where dependencies are installed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: loopix, loopix_git_repo: "https://github.com/parmegv/loopix.git" }

License
--------

BSD

Author Information
--------------------

Rafael Gálvez Vizcaíno
