# Linux-Desktop-Install
Set of scripts for every popular Linux Distro that allows a user to install any desktop environment they choose without changing distros or having a headache 

NOTE: You must run these scripts as ROOT using either the root user or as a regular user with sudo
as they need to access your respective Linux distros package manager Ex:(APT, PACMAN, DNF)
Ex: # ./DEinstall-Arch.sh
OR
Ex: sudo ./DEinstall-Arch.sh

These scripts are very much Alpha quality and might not work they were just made by a kid in college
I'm in the process of learning these things please be patient :)

Check the releases for the Scripts :)

I have provided some basic documentation and clarifications for the scripts down below. For your convinence I have included a Text file in the releases with the documentation as well.

What are these scripts: These are bash shell scripts that I created that automate the installation of a desktop enviornment that better suits you instead of having to change linux distros which are a headache for most people.

How do I get started: Firstly you want to check out my releases page and download the script that matches to your distrobution. If your unsure, I have made a Generic list to choose from. If your distro isn't in the list as there are so many to keep track of, a generic google search or your distrobutions basic documentation will tell you.

Releases: https://github.com/supergamer9787/Linux-Desktop-Install/releases


Anyone with these distros will want to use the Debian install script:

1. Debian Linux (of course)
2. AntiX Linux
3. Devuan Linux
4. MX Linux
5. Deepin Linux
6. kali Linux
7. Parrot OS Linux
8. Raspbian (Love the rasberry PI its awesome)
9. PureOS Linux
10. Linux Mint Debian Edition (YES ITS DIFFERENT FROM LINUX MINT DO NOT CONFUSE THEM)

Anyone with these distros will want to use the Ubuntu script:

1. Ubuntu Linux (of course)
2. Kubuntu Linux
3. Xubuntu Linux
4. Lubuntu Linux
5. Ubuntu Budgie Linux
6. Ubuntu Mate Linux
7. Ubuntu cinnamon Linux
8. Linux Mint (My personnel favorite for new users BTW)
9. Elementary OS Linux
10. Zorion OS Linux
11. Pop OS! Linux
12. KDE neon Linux

Anyone with these distros will want to use the Fedora script:

1. Fedora Linux (of course)
2. Nobara Linux
3. Ultramarine Linux
4. RisiOS Linux
5. Qubes OS Linux
6. Berry Linux
7. Clear OS Linux

Anyone with these distros will want to use the Arch script:

1. Arch Linux (of course)
2. Manjaro Linux
3. ArchBang Linux
4. Antergos Linux (Depreciated)
5. EndeavourOS Linux
6. Artix Linux
7. Archlabs Linux
8. Garuda Linux

What to do after downloading the correct script for my distro: Your browser most likely saved the script to your donwloads folder in your home directory. Simply open a terminal and type "cd Downloads".

How to execute/use the script: Fist things first you will need to make the script execuatble before you can use it. Its a neat security feature in linux to stop files with bad intent from using it. Don't worry my code is safe, check it out yourself if you don't believe me. To make the script execute simply type "chmod +x NAMEOFSCRIPT" What this does is changes the files permissions so its executable. Next type "sudo ./NAMEOFSCRIPT" Afterwards simply follow the prompts to install the desktop enviornment of choice and reboot when its finished.

I get an error stating "please run this script as root or with sudo": This happens when you don't have the proper permissions with your user to execute the script. If your not using the root account on your Linux system you will need to type sudo before executing the script as the script needs to access your distrobutions package manager (See above).

I get a message mid install about what display manager to choose: A display manager is what you see when you first boot into your Linux system. It allows you to login to your user and lets you choose your desktop enviornment. while you can interchange display managers with different desktop enviornments, its best to use the display manager the desktop enviornment uses by default. The list below tells you which one to select.

Gnome: GDM3
KDE Plasma: SDDM
XFCE: Lightdm
LXQt: Lightdm
Cinnamon: Lightdm
MATE: Lightdm
LXDE: Lightdm
Budgie: Lightdm
Deepin: Lightdm

What happens if I use the wrong script for my distrobution: Nothing, the script will throw an error related to apt, dnf or pacman command not found. This happens because Debian, Fedora, Ubunutu and Arch have different package managers from each other except for Debian and Ubuntu. While they use the same package manager, they have different repositories so they do NOT work interchangably.
