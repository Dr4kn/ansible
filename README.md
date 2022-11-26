# About ansible

It is a configuration tool primarily for Linux machines that works over ssh (and can be used locally).
You specify your desired state and ansible does to work to get it into that.

## Perquisites

Because I have files that I am either not allowed to (e.g. copyright) or won't (passwords) publish in this repo there is another private repo I sometimes download things from.
Therefore some local setup beyond the installation is required to run some scripts.

## Setup

To install it on your machine follow the [documentation](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html).
Clone this repo.
Install `python3-apt` with your package manager.
Run `ansible-playbook configure_ansible_host.yml -l local`.
This installs every package that is required by some roles used in this repo.
