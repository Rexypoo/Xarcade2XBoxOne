Xarcade2XboxOne
================

_Xarcade2XboxOne_ is a fork of Xarcade2Jstick with a more typical Xbox One button mapping.

_Xarcade2Jstick_ exclusively captures the keyboard events of the __Xarcade Tankstick__ and maps these events to corresponding events on two virtual game pad devices.

_Xarcade2Jstick_ was originally written as a supplementary tool for the [RetroPie Project](http://blog.petrockblock.com/retropie/). Using this tool allows the usage of the auto-config capability of [RetroArch](http://themaister.net/retroarch.html), a central component of a RetroPie installation.

## Usage

Your Xarcade will appear as two gamepads and can be used accordingly. There are also some special combinations of buttons that have special meaning:

* P1 select + P1 start = TAB
* P2 select + P2 start = ESC

The select buttons are the front buttons on each side of the joystick. The start buttons are the white top-center buttons.

## Downloading

If you would like to download the current version of _Xarcade2XBoxOne_ from [its Github repository](https://github.com/rexypoo/Xarcade2XBoxOne), you can use this command:
```bash
git clone https://github.com/rexypoo/Xarcade2XBoxOne
```

## Building and Installation

To build Xarcade2Jstick follow these commands:
```bash
cd Xarcade2XBoxOne
make
```

If everything went fine you can install with the command
```bash
sudo make install
```

## Installation as Service

You can install _Xarcade2XBoxOne_ as daemon with this command:
```bash
sudo make installservice
```

## Uninstalling the service and/or the binary

You can uninstall the daemon with this command:
```bash
sudo make uninstallservice
```

You can uninstall the binary with this command:
```bash
sudo make uninstall
```

<br><br>
__Special thanks to Florian [petrockblock.com](http://blog.petrockblock.com) for Xarcade2Jstick__
