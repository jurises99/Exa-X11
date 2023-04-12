#X11 setup (DXVK) for exagear
this is a simple script to setup X11 environment on Termux X11

#special thanks

[Herick75](https://github.com/Herick75/Box4Droid)
for the codes

# How to install?  

First you need to install [Termux](https://f-droid.org/en/packages/com.termux) and [Termux-x11](https://github.com/termux/termux-x11/actions/runs/4385798707).  After installing them, just copy the command `curl -o install https://raw.githubusercontent.com/jurises99/Exa-X11/main/Scripts/install && chmod +x install && ./install` and paste it in the Termux terminal and wait until the installation completes.

# How to start X11?

just type "x11" without qoute

# known issues

For some reason, when you go to install Termux and use the `pkg update -y` command for the first time, it may happen that you get some error and it is not possible to continue the installation, if that happens, just delete the Termux data and try again.

![Screenshot](Docs/InShot_20230402_231621771.jpg)

And there are probably other issues, so feel free to open an issue.

# Third party applications

[Box86 by ptitseb](https://github.com/ptitSeb/box86) MIT license

[Proot under Termux](https://github.com/termux/proot) GPL-2.0 license

[Anlinux Ubuntu Rootfs](https://github.com/EXALAB/Anlinux-Resources/tree/master/Rootfs/Ubuntu/arm64) GPL-2.0 License

[DXVK](https://github.com/doitsujin/dxvk) Zlib license

[Termux-app](https://github.com/termux/termux-app) GPLv3 license

[Termux-x11](https://github.com/termux/termux-x11)

[Wine](https://wiki.winehq.org/Licensing)
