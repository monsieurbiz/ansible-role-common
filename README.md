# Ansible Common Role

The role installs some often used programs.

It also updates the server packages :joy:.

## Requirements

* Ansible version 2.*

# Role Variables

You can override all the variables in `defaults/main.yml` in your own vars.

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.common }

## License

MIT

## Authors

* Jacques Bodin-Hullin - [@jacquesbh](https://twitter.com/jacquesbh)
