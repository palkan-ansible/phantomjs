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
| phantomjs                | phantomjs-1.9.7-linux-x86_64        | Binary name |
| phantomjs_url                 | 'https://bitbucket.org/ariya/phantomjs/downloads/{{ phantomjs }}.tar.bz2' | |

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.phantomjs
```
