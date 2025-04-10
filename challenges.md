# Challenges!

## 1.

Create a task in your playbook that just debugs a funny message in the console

## 2.

Create a user on the server

## 3.

Create a role titled `common` that installs the following programs

- dnsutils
- git
- btop

This role should also update the server before installing the tools

## 4.

Create a role titled `nginx`. Remember roles have to be in the `roles` directory.

This role should install the nginx web server on the target host, and ensure nginx is started at boot. Verify this by accessing the server on port 80 to see the default nginx site

## 5.

Make a super basic html website. Transfer that site to `/var/www/my_site`

Configure nginx using ansible templates to host that website on port 80

## 6

Recreate tasks 1-4 on the server using Ansible!
