## iPerf AC
A customized iPerf with Access Categories (BK, BE, VI, VO).
Currently extremely work in progress.
Because patch file comes from a different iPerf version, it must be applied manually (but in this case is already applied).

### Notes

This is Iperf v2.0.x, a tool for measuring Internet bandwidth performance.
See the doc directory for more documentation.

Briefly:

Do one-time if needed:
  dnf install gcc
  dnf install gcc-c++
  dnf install automake

then to build do:
  ./configure      -- configure for your machine
  make             -- compile Iperf
  make install     -- install Iperf, if desired, from root

and to use:
  iperf -s               (on machine "foo.bar.edu")
  iperf -c foo.bar.edu   (on some other machine)
  iperf -h               (for help screen)
  iperf -v               (for version information)

and for more information (requires make install)
  man iperf

Finally, see INSTALL, doc/RELEASE_NOTES, and doc/DESIGN_NOTES for a bit more

The SOURCE CODE is the AUTHORITATIVE source. Any COMMENTS found in the source ARE NOT.

Copyright 1999, 2000, 2001, 2002, 2003, 2004
The Board of Trustees of the University of Illinois
All rights reserved
See UI License (doc/ui_license.html) for complete details.

More copyright per years 2014 - 2020
Broadcom Corporation
All Rights Reserved

$Id: README,v 1.1.1.1 2004/05/18 01:50:44 kgibbs Exp $
