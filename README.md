# nginx-php-fpm installation on Debian.

Software version.

Ansible 2.2

Debian 9

php 7.0

nginx 1.10


run command: ansible-playbook -i /etc/ansible/roles/nginx-php-fpm/defaults/static.cfg --connection=local -s /etc/ansible/roles/nginx-php-fpm/nginx.yml

for successfully run playbook, dont forget add in /etc/ansible/ansible.cfg after [defaults]

invalid_task_attribute_failed=False
