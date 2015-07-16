Downloading
-----------

Click on the links below to download the packages.

* [ipe-7.1.8-src.tar.gz](/otfried/ipe/raw/master/releases/7.1/ipe-7.1.8-src.tar.gz):  Sources for building Ipe
* [ipe-7.1.8-win.zip](/otfried/ipe/raw/master/releases/7.1/ipe-7.1.8-win.zip): Binary package for Windows 7 and higher
* [ipe-7.1.8-winxp.zip](/otfried/ipe/raw/master/releases/7.1/ipe-7.1.8-winxp.zip): Binary package for Windows XP and Vista
* [ipe-7.1.7-mac.dmg](/otfried/ipe/raw/master/releases/7.1/ipe-7.1.8-mac.dmg): Binary package for Mac OS 10.8 or higher (may work on 10.6 and 10.7)



Patch
-----

If you need the Voronoi Diagram ipelet on Windows in Ipe 7.1.8, unzip
the file [patch-7.1.8-win.zip](/otfried/ipe/raw/master/releases/7.1/patch-7.1.8-win.zip) at the same place where you unpacked Ipe.  It replaces *qvoronoi.dll* with a working version.




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

