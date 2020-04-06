# AutomateSupermicroMotherboard
Repository containing Ansible playbooks for automating Supermicro Motherboard (bios and ipmi bmc)

# Getting Started
These playbooks have been used to automate updating Supermicro Motherboard from RHEL using Ansible.
It is required to download the correct bios file and ipmi/bmc firmware from Supermicro website.
These files needs to be uploaded to the Ansible server, in the relevant directory mentionned in the playbook.
The playbooks needs to be slighty modified to be adapted to the required setup (paths, file name...).
There are cleanup tasks contained in the playbook, to ensure the operation does not leave unwanted leftovers.

# Contributing
Everyone is welcome to contribute. Having said that, usually each motherboards are different and the tools evolve. Doing a "one tool for all"
does not seems realistic. Therefore, this playbook can be use as a starting point and needs to be modified by each users.

# Author:
Jean-Sébastien Tougne jtougne@redhat.com

