This repository holds configuration and policy information for remotely configuring instances of [Porteus Kiosk](https://porteus-kiosk.org).

If you have no special requirements, you can get good results by configuring an instance to use this management URL:

**https://robisaacnz.github.io/kiosks/generic**

That will configure an instance with:
* Wired ethernet connectivity
* An ad-blocker
* Sessions that end when the last window is closed
* Automatic cleanup

The syntax for controlling remote settings can be tricky, especially for pushing browser policies. You can fork or otherwise borrow this repository as a template for managing your own instances, or just use this one for a simple automatic configuration.

https://robisaacnz.github.io/kiosks/refurb is a config suitable for refurbishing older PCs.
https://robisaacnz.github.io/kiosks/refurb32 is a custom config optimised for Porteus Kiosk 3.7, the last 32-bit version available. It has a number of settings to improve performance on very old hardware.