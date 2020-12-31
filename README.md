# AfterArchOS
Meta-distro installable on Arch with own package manager and layers (repos).

# Installation
NOTE!: This will delete pacman and all arch stuff!!!!! You can do it at your own risk!
  - https://github.com/glowiak/afterarchos/releases/download/current/aao-install-latest.cpio.xz
  - Download this file and type following commands in downloads directory
  - xz -d aao-install-latest.cpio.xz
  - cpio -i < aao-install-latest.cpio
  - And type as root:
  - bash install.sh
  - Next reboot computer, open terminal and sync mainlayer layer:
  - sysconf -s mainlayer
  - Done, recommended is to install it on vm.

# No X pkgs on mainlayer
mainlayer layer doesn't contain X packages, so recommended is to install X from pacman before installing afterarchos.
# No Microsoft apps on mainlayer
mainlayer doesn't contain Microsoft apps, in orded to install those packages you have to add 'msprogs' layer.
