# dns

[![Build Status](https://travis-ci.org/m31271n/ansible-role-dns.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-dns)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.dns-blue.svg)](https://galaxy.ansible.com/m31271n/dns)

Ansible role that sets DNS.

## Requirements

None.

## Role Variables

+ `dns_nameservers`: `[ '8.8.8.8', '8.8.4.4' ]`
+ `dns_file_path`: `/etc/resolv.conf`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.dns
      dns_nameservers: [ '223.5.5.5', '223.6.6.6' ]
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
