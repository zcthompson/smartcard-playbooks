# smartcard-playbooks
Smart Card Playbook Examples v 1.03

Example playbooks for Ansible FreeIPA role.  Just drop in files to appropriate role locations

The client config playbook assumes the config-client-for-smart-card.sh script is in the files directory on the ipaclient role, this repository contains it, there is also the assumption the controller node can connect to the DoD website public or private to obtain certs.

Thank you to Zach/Dean for helping with password complexity issue identification

August 2022

Role has been updated to run in AAP w/ execution environment that contains rhel_idm collection.

Added in replica deploy w/DNS bug fix to module_utils
