Setup
=====
1. `git submodule init && git submodule update`
1. `gem install librarian-ansible`
1. `librarian-ansible install`
1. Review the roles to provision in ./Vagrant file (ansible.tags)
1. `vagrant up`


Optional Setup
--------------
To make repeat provisioning faster, we can cache some of the downloaded packages by installing vagrant_cachier.
