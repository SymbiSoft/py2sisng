# Welcome #

Python-to-SIS, the next generation (py2sisng) is the easiest cross-platform way to create [Symbian OS™](http://www.symbian.com/) installation packages (SIS) from [Python for S60](http://sourceforge.net/projects/pys60) scripts. py2sisng is an open-source program, under the GNU [GPL](http://www.gnu.org/licenses/gpl.html) license.


# Requirements #

  * [Python®](http://www.python.org/) v2.0 or greater, tested with Python v2.2 and v2.3
  * Either
    * genaif binary
    * makesis binary
  * or
    * A working C++ compiler, preferably [GCC](http://gcc.gnu.org/)
    * [zlib](http://www.zlib.net/) library and headers

SIS files made with py2sisng work on S60 1st and 2nd Edition phones. (See [Ensymble](http://ensymble.googlecode.com/) for software to generate SIS packages that work on 3rd Edition phones.) A list of editions for Nokia phones is available from [Forum Nokia](http://www.forum.nokia.com/devices/matrix_s60_1.html). S60 phones from other manufacturers should also work with py2sisng-generated packages.


# Download #


## Latest ##

v0.95 2006-04-02: [py2sisng-0.95.tar.gz](http://py2sisng.googlecode.com/files/py2sisng-0.95.tar.gz) (105 kB)

Changes:

  * Python for S60 was released under an open-source licence in January 2006. As it is now possible to include the required templates with py2sisng, there is no need to download and unpack the huge [SDK from Forum Nokia](http://www.forum.nokia.com/python) anymore. Python for S60 v1.3.1 templates are identical to those in the previous version (v1.2).
  * Patched makesis and genaif to be endian-neutral. The programs no longer require patching on big-endian machines (PPC, for example). In addition, the makesis patches fix some OS X specific issues.
  * Changed every occurrence of "Series 60" to "S60", due to the official name change in November 2005.
Older versions


## Older versions ##

v0.94 2005-10-25: [py2sisng-0.94.tar.gz](http://py2sisng.googlecode.com/files/py2sisng-0.94.tar.gz) (87 kB)

Changes:

  * Started using Python for S60 v1.2 templates.

v0.93 2005-10-18: [py2sisng-0.93.tar.gz](http://py2sisng.googlecode.com/files/py2sisng-0.93.tar.gz) (87 kB)

Changes:

  * Original application directory structure is now preserved in install packages.
  * Implemented application UID and SIS version detection from source file.
  * Default SIS file name now contains a version number.

v0.92 2005-09-09: [py2sisng-0.92.tar.gz](http://py2sisng.googlecode.com/files/py2sisng-0.92.tar.gz) (87 kB)

  * First public version


# Project history #

  * **2008-10-22**
> Moved project to [Google Code](http://code.google.com).
  * **2007-01-05**
> Added links to [Ensymble](http://ensymble.googlecode.com).
  * **2006-04-02**
> Version 0.95 released.
  * **2005-10-25**
> Version 0.94 released.
  * **2005-10-18**
> Version 0.93 released.
  * **2005-09-27**
> Added a note about py2sisng in the [GnuPoc Wiki](http://www.symbianos.org/cgi-bin/eblog/gnupoc.cgi?GnuPocToDo).
  * **2005-09-09**
> First public release


# Related links #

  * [Python for S60](http://sourceforge.net/projects/pys60) on [SourceForge](http://sourceforge.net)
> Application templates used in py2sisng are from the original py2sis, which has been released under an open-source license.
  * The [Ensymble](http://ensymble.googlecode.com) developer utilities for Symbian OS
> Ensymble generates SIS packages for S60 3rd Edition phones.
  * [Python for S60 discussion board](http://discussion.forum.nokia.com/forum/forumdisplay.php?f=102)
> Where questions about py2sisng are answered.
  * Rudolf König's [sdk2unix](http://www.koeniglich.de/symbian_sdk_on_unix.html)
> py2sisng uses, and includes the source code to, the genaif program from sdk2unix.
  * makesis for Linux from [GnuPoc](http://gnupoc.sourceforge.net/)
> Source code to a Linux-compatible version of makesis is included with py2sisng.
  * [HOWTO develop Symbian apps using Mac OS X](http://simonwoodside.com/dev/symbian/howto.html) from Simon Woodside
> These are very good instructions for setting up Symbian C++ SDK and sdk2unix, on OS X and other UNIX variants.


---

Copyright © 2005, 2006, 2007, 2008 Jussi Ylänen