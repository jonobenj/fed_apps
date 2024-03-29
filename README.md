Fedora Application Installs
=========

This role loops through and installs all required applications

Application List
----------------

#### DNF Packages

* steam
* git
* vim
* firefox
* onedriver
* gnome-tweaks
* thunderbird
* openrgb
* joystick-support
* pavucontrol
* lutris
* winetricks
* mangohud
* ~~bibata-cursor-themes~~ |  *Package missing from repo currently*
* timeshift
* telnet
* nmap
* radeontop
* lm_sensors
* conky
* htop
* bless
* hwinfo
* i2c-tools
* ~~gamescope-3.11.49-1.fc38~~  |  *Fedora 39 only has 3.12.5-1.fc39, will require testing with Star Citizen*
* collectd-sensors
* krita
* kdenlive
* flatpak

#### Flathub Apps

* spotify
* discord
* gdm settings
* minecraft

#### Repos

* onlyoffice.repo
* onlyoffice-desktopeditors

Requirements
------------


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---

- name: Fedora Build Playbook
  hosts: all
  tasks:
    - name: Run Fedora Build Role
      ansible.builtin.include_role:
        name: fed_apps
```

License
-------

BSD

Author Information
------------------

jonobenj
