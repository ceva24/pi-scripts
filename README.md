Raspberry Pi Utility Scripts
=============

A set of utility scripts for Raspbmc RC4.

Introduction
------------

A set of personal utility scripts for a Raspberry Pi running Raspbmc RC4. This repo is related to a blog post about configuring a Raspberry Pi, located [here](http://www.ceva24.co.uk/the-pi-and-i/).

These files are stored for posterity, as in reality the later releases of Raspbmc likely handle this functionality automatically.

Features:

*  Mounting of external device at `/dev/sda1` to `/media/usb`.
*  Configuration of a public Samba connection to the external device.
*  A clean shutdown script.

Install
-------

1. Place the scripts onto your Pi at the directories indicated by the structure of the repository. Remember to perform Windows-Unix EOL conversion
2. `chmod` relevant scripts with appropriate executable permissions.
3. Add the `mountdrive` script to the boot procedure with `sudo update-rc.d /etc/init.d/mountdrive defaults`.

Contribution
------------

Feel free to fork this project and modify the scripts to align with your configuration.
