# czexpressvpn
Graphical interface for ExpressVPN on Linux

ExpressVPN (https://www.expressvpn.com) is a commercial provider of VPN
services that supports all operating systems, including Android.  However, it
only provides a command line tool for Linux systems.

This application is a small graphical interface to ExpressVPN on Linux.  It
provides a system tray icon.  A click on the icon opens a short menu with
either a disconnect option, or with several connect options, depending on the
current connection status.

# Installing

Copy file `czexpressvpn` to any directory in your $PATH variable.  If
necessary, make the file executable (`chmod +x /chosen/path/czexpressvpn`).

ExpressVPN needs to be installed separately following the instructions provided
by the vendor.
