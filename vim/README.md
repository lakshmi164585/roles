Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

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
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

```
first we have to install manually java 11 and 17 verdsions 

```
   java 11 manual installation commands
  Refer Here:https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-22-04
      sudo apt update
      sudo apt install openjdk-11-jdk -y
      java -version
```
  java 17 manual instasllation
  Refer Here:
    Sudo apt update
    Sudo apt install openjdk-17-jdk -y
    Java —version
```
Write a playbook for each individually done by manual commands
Create roles for that playbook
Each role having a seperate folder by automaticcally called roles
That roles are push into local machine by sftp command line
command for pushing roles into local machine 
    sftp user@publicip  =====ansible user 
    login to sftp
    get -r filename
    bye === exit
    start . === open files in local machine
    code . ==== open files in vscode

```
Now we are moving or pushing that roles (what we are created ) into git hub repository
```



