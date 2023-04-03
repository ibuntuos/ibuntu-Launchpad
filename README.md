# iBuntu-Launchpad
The iBuntu version of Apple's/MacOS Launchpad application. The shortcut is meant to be placed on a dock as a keyboard-free alternative to pressing Super+A.

Forked Version to be used with iBuntu


<p align="center">
  <img src="https://raw.githubusercontent.com/ibuntuos/ibuntu-Launchpad/master/launchpad-1.0/launchpad.pngg" height="150" width="150">
</p>

## Installation
Install the dependency by opening Terminal and running:
```
sudo apt install xdotool
```

[Download the deb installer file](https://github.com/ibuntuos/ibuntu-Launchpad/blob/master/launchpad-1.0.deb)

Open the deb file and proceed with installation

Open Terminal and run:
```
xdg-open /usr/share/applications
```
or navigate to the ```/usr/share/applications``` folder manually

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/Ubuntu-Launchpad/master/images/applications-folder.png">
</p>

Drag the Launchpad icon onto the dock

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/Ubuntu-Launchpad/master/images/dock.png">
</p>

Done!

<br />
<br />
<br />
<br />


## Notes
Thanks to https://blog.packagecloud.io/eng/2016/12/15/howto-build-debian-package-containing-simple-shell-scripts/ for providing a great starting point with regard to packaging shell scripts into deb files

Icon made by Pixel Buddha from www.flaticon.com
