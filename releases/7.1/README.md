Versions
--------


ipe-7.x.y-src.tar.gz:  Sources for building Ipe

ipe-7.x.y-win.zip:     Binary package for Windows 7 and higher

ipe-7.x.y-winxp.zip:   Binary package for Windows XP and Vista

ipe-7.x.y-mac.dmg:     Binary package for Mac OS 10.8 or higher (may work on 10.6 and 10.7)

Ipe 7.1.8 (2015-07-11)
----------------------

 * (Partial) support for MacOS retina displays.  You need to set
   prefs.retina to true to enable this.

 * Fixed compilation of qvoronoi ipelet on Mac OS X (bug #31).

 * Now using standard libjpeg API for embedded JPEG images, rather
   than the TurboJPEG API.  Therefore Ipe now compiles with either
   JPEG library.  Thanks to Michael Thon for the patch (#32).

 * IPEBUNDLE variable to compile Ipe without references to the file
   system. 

 * IPENOGESTURE variable to compile Ipe for Windows Vista and older.

 * Fixed Document properties dialog (bug #33).

 * Fixed first entry in layer list popup menu.

 * Fixed crash in Voronoi ipelet on Windows (#5).

