Role Name
=========

This role is just a quick sample to show what can be done with Ansible Templating 

Requirements
------------

Anible must be installed

Role Variables
-----------
The current variables are 
environ     options=Dev, QA, PROD_BLUE, PROD_GREEN
 

Run
-------
From the top level run 

ansible-playbook -i host sample.yml --extra-vars="host_group=mycomputer environ=Dev" --ask-vault-pass



License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
