# Requirements
- The inventory/hosts file is configured with the mount_dir configured to /opt/ansible.  This directory must exist localally on the execution nodes
- The report, backup and isos directories need to also be created beneath the /opt/ansible directory and permissions need to be setup to allow reading the isos directory and reading/writing to the report and backup directories
- big-ip .iso amd .md5 files need to be copied into the /opt/ansible/isos directory
- 
