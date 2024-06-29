# Dankcuddlybear's PKGbuilds
Meta-packages and tweaks for Arch Linux.

# How to add this repository
1) Add the required keys to Pacman keyring.
~~~
sudo pacman-key --recv-keys 0F290EA682B40750
sudo pacman-key --lsign-key 0F290EA682B40750
~~~
2) Add the following to /etc/pacman.conf:
~~~
[dankcuddlybear-pkgbuilds]
Server = https://raw.githubusercontent.com/dankcuddlybear/pkgbuilds/main/_repo
~~~
3) Update Pacman databases:
~~~
sudo pacman -Sy
~~~
That's it, you are now ready to install and use these packages!
