Chef-Server Blueprint
======================

This blueprint creates an instance and installs chef-server.

Requirements
-------------
 1.AWS
 2.Azure
 3.Openstack
 4.Vcenter
 5.Xenserver

Operting System
----------------
 1. Centos
 2. Ubuntu
 
Usage
------
 1. Upload the blueprint to calm.
 2. Change Aws provider in overview tab.
 3. Change Credentials for chef-server under credentials tab.
 4. Deploy the blueprint.
 5. By default it installs chef-core, reporting and pushjobs. You can change these under node taks.
