# Ansible Raspberry Pi Debian Image Custom Setup

Ansible script for creating raspi sdcard

### Setup sdcard

1. Configure: `inventory.yml`
2. Run: `ansible-playbook -i inventory.yml playbook.yml -K`

### Available tags
 - download-img : Downlaod raspi debian image
 - download-pkg : Downlaod raspi debian additional packages
 - download-all : Perform all download operations
 - install-img  : Install raspi image in a new sdcard
 - install-pkg  : Add additional packages to `/home/` in sdcard
 - install-cmd  : Install script in sd card to setup SSH, install packages and connect to Wifi
 - install-all  : Perform all install operations
