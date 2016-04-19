Role Name
=========
[![license][2i]][2p]
[![twitter][3i]][3p]

A base role for dependencies.

Description
-----------

Nothing too fancy. This role installs base development tools for the available platforms for the role. It also installs git,svn,hg for version control dependencies. The role updates all the packages in the platform before the provision.

Usage
-----

Only need to append to your playbook.

``` yaml
- hosts: servers
    roles:
        - common
```

Author Information
------------------

[Alejandro Baez][1]

[1]: https://keybase.io/baez
[2i]: https://img.shields.io/badge/license-BSD_2-green.svg
[2p]: ./LICENSE
[3i]: https://img.shields.io/badge/twitter-a_baez-blue.svg
[3p]: https://twitter.com/a_baez
