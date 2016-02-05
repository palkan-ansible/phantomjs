PhantomJS
========

Installs PhantomJS from binary.

Installation
--------------

`ansible-galaxy install palkan.phantomjs`

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value |  Description    |
|-----------------------------|---------------|-----------------|
| phantomjs_version           | phantomjs-2.1.1-linux-x86_64 | Version
| phantomjs_bin                | {{ phantomjs_version }}/bin/phantomjs        | Binary pathname |
|phantomjs_archive              | {{ phantomjs_version }}.tar.bz2 | Archive name
| phantomjs_url                 | 'https://bitbucket.org/ariya/phantomjs/downloads/{{ phantomjs_archive }}' | |

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.phantomjs
```
