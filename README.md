## percona-client 

[![Build Status](https://travis-ci.org/Oefenweb/ansible-percona-client.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-percona-client) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-percona--client-blue.svg)](https://galaxy.ansible.com/list#/roles/4823)

Set up a [percona-server](https://www.percona.com/software/mysql-database/percona-server) client in Debian-like systems.

#### Requirements

None

#### Variables

* `percona_client_version`: [default: `5.5`]: Version to install
* `percona_client_install`: [default: `[]`]: Additional packages to install

## Dependencies

None

## Recommended

* `percona-server` ([see](https://github.com/Oefenweb/ansible-percona-server)

#### Example

```yaml
---
- hosts: all
  roles:
    - percona-client
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-percona-client/issues)!
