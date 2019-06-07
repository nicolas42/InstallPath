# InstallPath
Notes on different programs, how to install things, quality tools

## Furious Port Scanner
Fast port scanner written in golang 
https://github.com/liamg/furious

Installation
apt install libpcap-dev
go get -u github.com/liamg/furious

Installation only worked on linux and required packet capture library to be installed as well

## Turn capslock into ctrl in linux using xmodmap
https://wiki.archlinux.org/index.php/Xmodmap#Turn_CapsLock_into_Control

~/.Xmodmap
clear lock
clear control
keycode 66 = Control_L
add control = Control_L Control_R
