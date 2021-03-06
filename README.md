CECREMOTE

CecRemote is a remote control plugin for the MediaPortal media center software (http://www.team-mediaportal.com). 
It allows you to control MediaPortal with your TV’s remote using HDMI-CEC signals.



Features

- fully customizable key mappings
- automatically power on TV when MediaPortal starts
- automatically power off TV when MediaPortal is closed, system enters sleep or computer is powered off
- option to set the HDMI device type that is reported to TV


Requirements

- libCEC compatible USB-CEC adapter (from Pulse-Eight)
- TV that supports HDMI-CEC


Getting started

Once you have installed and configured MediaPortal, download latest version of the plugin and install it. Plugin is distributed in MediaPortal extension installer format, so installation is easy. Make sure that you have USB-CEC adapter drivers installed and adapter firmware is up-to-date. Set at least the correct HDMI-port from plugin settings and you’re ready to start controlling Media Portal with your TV’s remote.



Compilation

To compile CECRemote, you need Visual Studio 2010(+) and the following dependencies:

- Media Portal 1.6.x or newer (references to libraries in Media Portal install dir)
- libCEC < 3.1.0 (reference to LibCecSharp)




This project uses libCEC (https://github.com/Pulse-Eight/libcec)
libCEC(R) is a trademark of Pulse-Eight Limited.
