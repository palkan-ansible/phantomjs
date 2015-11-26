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
| phantomjs_bin                | phantomjs-1.9.7-linux-x86_64        | Binary name |
|phantomjs_archive              | {{ phantomjs_bin }}.tar.bz2 | Archive name
| phantomjs_url                 | 'https://bitbucket.org/ariya/phantomjs/downloads/{{ phantomjs_archive }}' | |

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.phantomjs
```
