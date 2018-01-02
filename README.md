Role Name
=========

#A brief description of the role goes here.

RHEL Tuner for Oracle 

It configures:

   1.  Memory settings in /etc/sysctl.conf
   2.  Huge Pages
   3. Limits settings in /etc/security/limits.conf
   4.  Shared Memory
   5.  Semaphores
   6.  Open file descriptors
   7.  Disabling transparent hugepages (only recommended for RHEL 6)
   8.  I/O scheduler

Ensure that the Oracle database is configured to use Huge Pages.

Requirements
------------

#Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

1. Oracle/DBA Group ID
2. SGA Value
3. Open FD (Can keep default as 65536)

Role Variables
--------------

#A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

#A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

#An optional section for the role authors to include contact information, or a website (HTML is not allowed).
Pravin Mali
