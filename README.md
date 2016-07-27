New Relic Servers package installer
=========

[![Build Status](https://travis-ci.org/primozcigler/ansible-newrelic-servers.svg?branch=master)](https://travis-ci.org/primozcigler/ansible-newrelic-servers)

Role for installing and running Ubuntu or Debian New Relic Servers package. More info in [official docs](https://docs.newrelic.com/docs/servers/new-relic-servers-linux/getting-started/new-relic-servers-linux#installation).

Role Variables
--------------

The only variable that should be set prior running this role is the `newrelic_license_key`. It is 40 chars long key you get in your New Relic account settings. I recommend saving it in [Ansible Vault](http://docs.ansible.com/ansible/playbooks_vault.html).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: primozcigler.newrelic-servers, newrelic_license_key: 42 }

License
-------

MIT

Author Information
------------------

Full stack developer, currently at [ProteusThemes](https://www.proteusthemes.com/).
