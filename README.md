# TempleOS-Unofficial


![Python on Temple OS (U)](https://raw.githubusercontent.com/tosrevive/TempleOS-Unofficial/master/screenshot.png?)

This is an unofficial continuation of Temple OS

[Releases](https://github.com/tosrevive/TempleOS-Unofficial/releases)

[Documentation](https://tosrevive.github.io/TempleOS-Unofficial)

This operating system is based almost entirely on [Temple OS](http://templeos.org)

It has documentation similar to the documentation of Temple OS located here: [https://templeos.holyc.xyz/](https://templeos.holyc.xyz/)

I plan to keep this unofficial version in line with the rules of the [Charter](https://tosrevive.github.io/TempleOS-Unofficial/Wb/Doc/Charter.html)

The goal here is to continue Terry's work unofficially by collecting bug fixes and new features.  There is room to add at least 15,000 lines between Adam, Compiler, and Kernel while still staying below the 100,000 line!  Let's show what Temple OS can do!

### Goals:

- Bug Fixes
- Add new features 
- Keep additions "Christian Friendly"

I hope to make things easier on new users by doing the following:

- Release graphics and text mode versions.  Text mode allows you to run Temple OS inside a Linux terminal using QEMU's curses option so it is much easier to copy and paste text between them.
- Release ISOS which have Terry's supplemental disc added to the /Extras folder since many people are interested in their content.
- Release ISOS which have both his supplemental content and other 3rd Party apps (which may or may not conform to the charter)

### Differences between this OS and Temple OS:

- Requires a processor which supports SSE instructions.  Pretty much every processor released after 1995 has these so it should not give anybody any trouble.  I opened the OS up to these instructions in case people want to make use of them.  I needed to be able to use them for my [TOS Micropython](https://github.com/tosrevive/micropython-tos) port.
- Adds back some features which were in Temple OS, but have been removed (such as BMP support)
- The slipstreamed versions have a /Extras folder that is not considered part of the OS.  It is simply additional software files slipstreamed into the normal charter conforming releases for the sake of convenience (so people can just mount the ISO.C files inside Temple OS and do not have to mess with changing virtual disks in virtual drives).

### Slipstreamed Extras includes:

- Terry's Supplemental discs 1-3 on the *_Sup releases
- Terry's Supplementals, [hgbd](https://github.com/tosrevive/hgbd) (Host guest block device driver), [virtio](https://github.com/tosrevive/bdt-virtio-blk) (virtio block device driver), and [Micropython](https://github.com/tosrevive/micropython-tos) on the *_Plus releases



