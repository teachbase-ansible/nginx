Nginx
========

Installs Nginx and setup apps (if provided).

Installation
--------------

`ansible-galaxy install teachbase-ansible.nginx`

Role Variables
--------------

`defaults/main.yml`

| Name                        | Description    | Example |
|-----------------------------|---------------|-----------------|
| nginx_apps          | A list of apps to add to nginx | - { name: 'my_app', config: 'my_app.conf' } |


Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - teachbase-ansible.nginx
```
