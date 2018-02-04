sysadmiral-ansible-visualstudiocode
=========

Install [Visual Studio Code][1] using the details for a yum/dnf repo described in the [docs][2].

Requirements
------------

Tested on Ansible 2.4+

Role Variables
--------------

* microsoft_signing_key_url - use this to override the default signing key url
* vscode_repository_url - use this to override the default repository url

Dependencies
------------

none

Example Playbook
----------------

    - hosts: localhost
      roles:
        - sysadmiral.sysadmiral-ansible-visualstudiocode

License
-------

MIT

Author Information
------------------

Written by [sysadmiral][5], 2018. You can find me on [twitter][3], [github][4] & [keybase][6]

[1]: https://code.visualstudio.com/ "Visual Studio Code"
[2]: https://code.visualstudio.com/docs/setup/linux#_rhel-fedora-and-centos-based-distributions "Running VS Code on Linux"
[3]: https://twitter.com/sysadmiral "twitter.com/sysadmiral"
[4]: https://github.com/sysadmiral "github.com/sysadmiral"
[5]: https://sysadmiral.xyz "sysadmiral.xyz"
[6]: https://keybase.io/sysadmiral "keybase.io/sysadmiral"
