![enter image description here](https://archlinux.org/static/logos/archlinux-logo-dark-1200dpi.b42bd35d5916.png)

# ansible-arch

Besides [Gentoo](https://www.gentoo.org/), [Arch](https://archlinux.org/) is my most favourite linux distribution. I'll use those ansible playbooks to speed up the creation of my own environment, so i'll be up & running in a few minutes on every system - virtual or on hardware.

## environment

`environment.yml` clones my config files from git. I can pass a parameter for cloning my [dwm](https://github.com/dme86/dwm) config, configure it and adding some more packages i need for my desktop (this is really cool, i know!).

**Example**:

    ansible-playbook environment.yml --extra-vars "desktop=True"
