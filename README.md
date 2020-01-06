Ansible Role: Saxon HE
=========

Ansible role that installs the Saxon XSLT and XQuery processor (java, HE)
http://saxon.sourceforge.net


Requirements
------------

Java 8 or above


Role Variables
--------------

    saxon_version: 9.9.1.6
    saxon_dir: "/usr/share/java"


Dependencies
------------

None


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: saxon }


License
-------

CC0
