# spooky-debian
My Setup Instructions for Debian.

INSTALL:

First download the latest net install disc for
debian (currently stretch).

Begin install when it gets to "Software selection"

DO NOT select

"Debian desktop environment" or

"... GNOME" or

"... Xfce" or

"... KDE" or

"... Cinnamon" or

"... MATE" or

"... LXDE"


free to select all other selections that are
not X11 related.

Then after install reboot and login as root

then edit 

/etc/apt/sources.list end of each line where main is add contrib and non-free:

contrib non-free

then run:

apt-get update

apt-get upgrade

apt-get dist-upgrade

apt-get update

apt-get install alsamixergui claws-mail faenza-icon-theme feh firefox-esr fonts-dejavu fonts-dustin fonts-liberation fonts-linuxlibertine fonts-uralic geany gexec gftp git gksu gogglesmm grsync jwm libreoffice lightdm mirage nitrogen rox-filer smplayer speedcrunch suckless-tools ttf-dejavu ttf-freefont ttf-liberation ttf-mscorefonts-installer ttf-staypuft vim whiptail wicd wmctrl xterm yad


After install done reboot computer.

You should now see a grapichal grub and boot with lightdm login to JWM session.

