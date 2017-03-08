ansible hosts
=============
[![Build Status](https://travis-ci.org/ypsman/ansible-hosts.svg?branch=master)](https://travis-ci.org/ypsman/ansible-hosts)

Setup entries in hosts file (/etc/hosts)

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.hosts
          hosts_entries: |
                        8.8.8.8 google.dns example.org
                        192.168.0.200   example.local
