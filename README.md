# Ophiuchus ISO

This repository contains the `ophiuchusISO` command line tool to build Ophiuchus from an
Ubuntu temporary chroot. It also contains some patches to original Ubuntu code
that makes Ophiuchus work properly, preventing any bug rendering.

This source code is a copy of the original Vanubuntu source code.

## Building

Non-Debian based distros will probably not offer debootstrap, which is required
for ophiuchusISO to work. This means you'll probably want to build the distro
on Debian or Ubuntu.

Run `vanubuntu.sh` to run the build.
