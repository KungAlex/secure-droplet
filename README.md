 [![Build Status](https://travis-ci.org/KungAlex/secure-droplet.svg?branch=master)](https://travis-ci.org/KungAlex/gitlab-docker-compose)

 

secure-droplet
==============

Secure a fresh Digitalocean Droplet 

Requirements
------------

Set password variable in vars.yml  
 
    mkpasswd --method=sha-512
    
Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
    
      vars_files:
         - vars.yaml
      
      roles:
         - kungalex.secure-droplet

Test Local
----------
    vargrant up
    vargrant provision
    

License
-------

MIT

Author Information
------------------

Alexander Kleinschmidt (kung4lex@gmail.com)