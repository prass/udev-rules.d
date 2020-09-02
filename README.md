# udev-rules.d

udev rules for my embedded debug tools

  * ST-Link V2/V2.1
  * J-Link
  * mySmartUSBlight
  * Saleae Logic

## Install rules
``
cp 99-tty.rules /etc/udev/rules.d/
``

## Add user to plugdev Group
``
usermod -a -G plugdev userName
``
