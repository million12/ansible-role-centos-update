# Ansible Role: CentOS Update with system-tools
[![GitHub Open Issues](https://img.shields.io/github/issues/million12/ansible-role-centos-update.svg)](https://github.com/million12/ansible-role-centos-update/issues)
[![GitHub Stars](https://img.shields.io/github/stars/million12/ansible-role-centos-update.svg)](https://github.com/million12/ansible-role-centos-update)
[![GitHub Forks](https://img.shields.io/github/forks/million12/ansible-role-centos-update.svg)](https://github.com/million12/ansible-role-centos-update)
[![GitHub release](https://img.shields.io/github/release/million12/ansible-role-centos-update.svg)](https://github.com/million12/ansible-role-centos-update)
[![license](https://img.shields.io/github/license/million12/ansible-role-centos-update.svg?maxAge=2592000)](https://github.com/million12/ansible-role-centos-update/blob/master/LICENSE)

---

Ansible role updates CentOS to the latest version and installing basic sysadmin tools.

It's a catchall for anything that needs to happen when you first spin up a new server that wasn't big enough to merit its own role.

### Requirements
Tested on CentOS 7 but should work on RHEL equivalents.

### Example Playbook

    - hosts: servers
      roles:
         - { role: million12.centos-update, tags: ['update'] }


---
### Author

Author: Przemyslaw Ozgo (<przemek@m12.io>)

This work is also inspired by [jeffwidman](https://github.com/jeffwidman)'s [work](https://github.com/jeffwidman/ansible-centos-bootstrap). Many thanks!


---
**Sponsored by [Prototype Brewery](http://prototypebrewery.io/)** - the new prototyping tool for building highly-interactive prototypes of your website or web app. Built on top of [Neos CMS](https://www.neos.io/) and [Zurb Foundation](http://foundation.zurb.com/) framework.
