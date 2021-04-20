# Arch For Humans

### Warning

It's very important to edit a little of the script for your use, if not:

- It will use Portuguese (Brazil) as the language and keymap.
- It will use thales as username.
- In S145 scripts it will try to connect to Wi-Fi with an SSID and password (plz don't go to my house coz you want internet, thx) that probably will not be correct for you.
- Be careful with the S145 scripts because they are for my laptop and it uses UEFI. (On the VirtualBox ones, there's an option for BIOS and UEFI, uncomment or comment them and be happy)

ArchForHumans is an script that tries to make the Arch installation more easy, but without taking the essential of it. It is composed by two scripts. I plan making a third one (for desktop and graphical programs), but for now, these two will be good for a base install (no desktop) of Arch Linux.

### ArchISO script

Is the first script that you should run. It's planned to be executed when you put the installation media on the PC or laptop. Once you've connected to internet, you can run those commands:

> git clone https://github.com/euthzless/ArchForHumans

> cd ArchForHumans

> sh ArchISO-VirtualBox

or:

> sh ArchISO-S145
