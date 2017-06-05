pi_gpio
=========

An easy way to handle GPIO for raspbian on Raspberry Pi 3, possible the Zero and Zero W

Requirements
------------

For now, no requirements, initial release will be a proof of concept

Role Variables
--------------

gpio: GPIO number

Dependencies
------------

No dependencies at this moment

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jonbrefe.pi_gpio, gpio: 42, write: 1 }
         - { role: jonbrefe.pi_gpio, gpio: 42 }

License
-------

GNU General Public License v3.0

Author Information
------------------

Original author: Jonathan Brenes <jbrenes@gmail.com>

