# ansible Collection - effem.vagrant

simple tooling for bootstrapping vagrant boxes.

some background on the tooling for which this collection exists:
- [ansible](https://www.ansible.com/)
- [vagrant](https://developer.hashicorp.com/vagrant)

this collection currently supports using base debian images with
tasks to customize the terminal and setup a local server using:
- [oh my bash](https://github.com/ohmybash/oh-my-bash)
- [ble.sh](https://github.com/akinomyoga/ble.sh)
- [nginx](https://www.nginx.com/)
- [ufw](https://wiki.debian.org/Uncomplicated%20Firewall%20%28ufw%29)

the end goal is to quickly bootstrap pentesting labs whether via
virtual machines or docker containers. additional tooling will be
included as needed.