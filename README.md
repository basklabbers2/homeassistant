# homeassistant
This project contains the basic files for an Ansible setup of Homeassistant Supervised.
It's mainly for my own purposes in order to quickly install and clean homeassistant supervised on a new machine.
Basic knowledge of Ansible setup required, including an machines setup with ansible.

It asumes a greenfield installation of Ubuntu with the following prerequisits:
- A
- B
- C

Files:
- ha-installer.yml (asumes a inventory and ansible.cfg)
- ha-installer.sh (copy of https://raw.githubusercontent.com/home-assistant/supervised-installer/master/installer.sh, removed the network change question)
