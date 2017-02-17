## Synopsis

This Ansible playbook acts as a wrapper for RDO and packstack.  By setting Ansible variables, the process for creating a demo environment in which to run OpenStack becomes measureable & repeatable.  Tying this Ansible playbook into a Vagrant hook also creates a CI/CD workflow environment.

## Code Example

ansible-playbook site.yml -i inventory.txt -vvvv

## Motivation

To reduce the headache of RDO.  Because admins are intrisically lazy.  To standardize accross Fedora, RHEL & CentOS.

## Installation

Install Ansible
Clone Repo
Change Directories
See Above

## API Reference

Place this behind Tower for a REST based solution!

## Tests

Test this sample by executing the playbook & then validating openstack-service status.

## Contributors

Mark West of Red Hat

## License

Apache 2 Licensed