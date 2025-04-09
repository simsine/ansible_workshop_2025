# friByte Ansible workshop 2025

**Welcome to the tasks of the friByte Ansible intro workshop!**

In this repo you will find a general structure of an Ansible project, i have already created the
"inventory" you should use.

## Requirements

The VMs are already created and joined to Tailscale. So they should be reachable, remember to have tailscale activated

## Rules

1. One VM pr person/team
2. No configuring the server with SSH, checking to see if task complete is alright
3. Everything must be done with Ansible

## Final challenge

At the end of this workshop, you will delete your VM, remake it and join in to tailscale. Then you should be able to recreate a similar config state to before using only a single ansible playbook run
