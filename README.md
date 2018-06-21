# Corporatrin-GTK
a GTK2,and GTK3 file for the Gnome-desktop


![s](https://cn.pling.com/img/b/7/7/2/b72f85db98df26124d4638bb592327aa7b1a.jpg)



Please, try and rate, comment. Any input or criticism is welcome.


## Issues:

You will notice that resizing the sidebar in nautilus behaves strange. This is not a bug. Visually the sidebar will not change (to keep it alligned with the headerbar), but you will still see the pointer for resizing. For this to work properly, pleas keep the sidebar-size small as possible.


## Requirements:

GTK+ 3.20 or later. Only standard (or Ubuntu) gnome-desktop is supported. Ready for Ubuntu 18.04
Disable gnome-extensions that reside on the headerbar because they mess up the headerbar-theming.

Window-buttons-layout (min/max/close) at the right side. (DO NOT PUT IT ON THE LEFT-SIDE)
No support for left-side window-controls! There will be no future support for left-sided buttons...

GTK2 ENGINES REQUIREMENT

- GTK2 engine Murrine
- GTK2 engine Pixbuf

Fedora/RedHat distros:
yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:
pacman -S gtk-engine-murrine gtk-engines

## What to do:

Extract and put it into the themes directory i.e. ~/.themes/ or /usr/share/themes/ (create it if necessary).Then change the theme via distribution specific tool like Gnome tweak tool or Unity tweak tool, etc. (If you use Snap-packages instead of app's from the normal repositories than definitely put the theme to /usr/share/themes/.
