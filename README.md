# Ansible Role: OpenBacchus Installer 

Ansible role for installing OpenBacchus on RHEL/CentOS or Ubuntu/Debian. Based on official [OpenBacchus](https://github.com/openbacchus/bacchus) installer. 

## Future Work

I am planning to automate some stuff...

## Requirements
This role requires:

- Ansible
- Crazy CLI Ninja skills
- Patience

## Supported Platforms

- [Ubuntu - 16.04 (Trusty Tahr)](http://releases.ubuntu.com/16.04/)
- [Ubuntu - 18.04 (Xenial Xerus)](http://releases.ubuntu.com/18.04/)
- [CentOS7](http://isoredirect.centos.org/altarch/7/isos/aarch64/CentOS-7-aarch64-Everything-1810.iso)
- [RHEL7](https://access.redhat.com/articles/754933)


## Role Variables

Will be here...

## Example Playbook


``` yaml
- name: Install => Open Bacchus 
  hosts: all
  gather_facts: true
  become: true

  roles:
   - bacchus-ansible

```

Author Information
------------------
Based on official [OpenBacchus](https://github.com/openbacchus/bacchus) installer. 

Modified by [Armagan Karatosun](https://github.com/armagankaratosun/).