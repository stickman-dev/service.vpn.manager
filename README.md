VPN Manager for OpenVPN
=======================

> [!IMPORTANT]
> This is a fork of [Zomboided/service.vpn.manager](https://github.com/Zomboided/service.vpn.manager), which is no longer maintained. This fork fixes NordVPN and PIA connections, which had broken as those providers changed how they work; other providers may still be broken.

NOTE : Kodi 19 Matrix version [here in pre-release](https://github.com/Zomboided/service.vpn.manager/releases/tag/6.9.3)

This add-on is a service for Kodi that allows the user to vary the level of
privacy required by automatically switching between different VPN
profiles/locations.

It can connect to a VPN on Kodi startup (on OS boot for LibreELEC installs) and
then maintain the VPN connection based on the add-ons being used. The perceived
location of the externally visible IP address is displayed upon connection.

A number of VPN providers are directly supported, or the user can add their own
VPN profiles.

Control of the VPN is also possible via a remote control button or hot key,
allowing the user to manually cycle between connections.

Full instructions can be found on the [GitHub wiki for this
project](https://github.com/stickman-dev/service.vpn.manager/wiki)
