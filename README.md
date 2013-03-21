heat-rpms
=========

(This repository is no longer maintained. For a more up to date spec file,
please see the files hosted at http://pkgs.fedoraproject.org/cgit)

Repo for creating rpm packaging for the heat projects:

Step 1: Override Makefile variables

Create a file local.mk and set any variables which should override the make
variables at the beginning of the file Makefile

linux% touch local.mk  

Step 2: Create RPMs

linux% cd heat-rpms  
linux% make  
