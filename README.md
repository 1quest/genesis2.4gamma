[![Build Status](https://travis-ci.org/borismarin/genesis2.4gamma.svg)](https://travis-ci.org/borismarin/genesis2.4gamma)

# Genesis Neuronal simulator, version 2.4

Sources for the  [_Genesis_ neural simulator](http://www.genesis-sim.org/), version 2.4.

# Installation intructions

Ye olde _configure_, _make_...

- ```cd genesis-2.4gamma/src```
- ```./configure``` or ```./configure --prefix=<install_path>```
- ```make```

This procedure has been verified to work on recent x86_64 Linuces and Mac OSX > 10.8


# Original README file

```

::

			       G E N E S I S

		   The GEneral NEural Simulation System
			     Version 2.4
           Last edited: $Date:Fri Oct 17 15:49:46 MDT 2014 $

Introduction
------------

This directory contains the distribution of GENESIS version 2.4.

A detailed list of source code changes from previous versions is provided in
genesis/ChangeLog.  New features of version 2.3 and 2.4 are described in
genesis/Doc/Changes.txt.

Directions for installing binary distributions may be found in README.bindist
in this directory. Directions for building and installing source distributions
are in src/README.  Be sure to read the directions
concerning the installation of the ".simrc" file.  Directions for printing
and using the documentation may be found in Doc/README.  The
Scripts/README file describes the demonstration and tutorial simulations
which are included with this distribution.

Description of GENESIS
----------------------

GENESIS is a general purpose simulation platform which was developed to
support the simulation of neural systems ranging from complex models of
single neurons to simulations of large networks made up of more abstract
neuronal components.  Most current GENESIS applications involve realistic
simulations of biological neural systems.  Although the software can also
model more abstract networks, there exist other simulation packages that
are more suitable for backpropagation and similar connectionist modeling.

A detailed guide to the GENESIS neuroscience tutorials and the construction
of GENESIS simulations is given in:

   The Book of GENESIS: Exploring Realistic Neural Models with the GEneral
   NEural SImulation System, Second Edition, by James M. Bower and David
   Beeman, Springer-Verlag (1998).  The free Internet Edition is available
   at http://www.genesis-sim.org/GENESIS/bog/bog.html

Additional hypertext documentation, including a beginners guide to
UNIX/Linux commands, can be found in genesis/Tutorials.

Source code contributed by GENESIS users which must be compiled is found in
src/contrib; other contributions, such as scripts and utilities are in contrib.

Obtaining GENESIS
------------------

GENESIS source and binary distributions can be obtained from:
http://sourceforge.net/projects/genesis-sim, and http://genesis-sim.org.

Machine dependence
------------------

GENESIS and its graphical front-end XODUS are written in C and are
known to run under many UNIX-based systems with the X Window System
(X11R5, X11R6, Xorg), as well as OSX and Windows with Cygwin. Most
recent experiences are with Fedora and Ubuntu. It has also been used
under various MS Windows virtual environments for running Linux.

Here is a partial list of tested older platforms:

* x86-based Linux systems:
   + Debian Linux with kernel 2.x
   + Fedora Core 2, 3, and 4
   + Gentoo
   + Mandrake Linux 7, 8, and 9.1 (but not 9.0)
   + Red Hat Linux 5, 6, 7, 8, and 9
   + Slackware 10
* 64 bit Linuces:
   + Fedora Core 3 and 4
   + Red Hat Enterprise
* x86-based FreeBSD 4.1
* Alpha with Debian 3.0
* IBM SP2 systems running AIX 4.2 and 4.3
* PPC-based Linux systems running LinuxPPC, SUSE 7.0, and OSX
* SGI MIPS-based systems running IRIX 5.x and 6.5.x
* Sun SPARC and x86 systems running Solaris 2.6, and 2.7

It is quite likely that GENESIS will also work on systems running other
versions of the operating systems listed above; however, the GENESIS
developers only have direct experience with the particular systems listed.

GENESIS may *fail* to work on DEC Alpha-based systems. Please let us know of
any experiences with this platform.

GENESIS has in the past worked on the following systems, but the developers
do not have these systems available for full testing and have not been able
to adequately verify that GENESIS 2.3 compiles and runs properly:

* Sun SPARC-based systems running SunOS 4.1.x
* Sun SPARC-based running Solaris 2.5/2.5.1
* HP-UX systems
* Intel Paragon
* DECStation running Ultrix 4.x or 3.x
* Cray T3E and T3D

We welcome feedback on experiences with these platforms.  If you attempt to
use GENESIS on these systems and have problem reports (or even better,
fixes), please contact the GENESIS maintainers.


GENESIS Users Mailing List
--------------------------

Serious users of GENESIS are advised to join the GENESIS
genesis-sim-users mailing list at
https://lists.sourceforge.net/lists/listinfo/genesis-sim-users.  Find
the latest new simulations, libraries of cells and channels,
additional simulator components, new documentation and tutorials, and
patches at the main GENESIS web site http://genesis-sim.org.

Disclaimer
----------

It should be understood that this software system is being provided for
general distribution as a public service to the neural network and
computational neuroscience communities.  We make no claims as to the
quality or functionality of this software for any purpose whatsoever and
its release does not constitute a commitment on our part to provide support
of any kind.

----------------
Copyright Notice
----------------

  Copyright 1988 - 2001 by the California Institute of Technology

  This program is free software; you can redistribute it and/or modify it
  under the terms of the GNU General Public License as published by the Free
  Software Foundation.  Portions of this program are in library form.  The
  libraries are also free software; you can redistribute them and/or modify
  them under the terms of the GNU Lesser General Public License as published
  by the Free Software Foundation; either version 2.1 of the License, or (at
  your option) any later version.

  This program is distributed in the hope that it will be useful, but
  WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
  General Public License for more details.

  You should have received a copy of the GNU General Public License and the
  GNU Lesser General Public License along with this program; if not, write to
  the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor,
  Boston, MA 02110-1301  USA.

  Recent additions to the GENESIS libraries are copyrighted by other
  institutions or authors, and are covered by the GNU General Public
  License (GPL), GNU Lesser General Public License (LGPL), or by other
  licenses that are compatible with the GPL and that do not restrict the
  free distribution of GENESIS.  These licenses appear with these modules.

  For a statement of the GPL, see the file "GPLicense".
  For a statement of the LGPL, see the file "LGPLicense".
```
