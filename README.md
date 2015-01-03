PatchELFmod
===============
**PatchELFmod** is a simple utility to modify header data of ELF executables
and libraries. It can change the dynamic loader ("ELF interpreter")
of executables, change existing DT_SONAME entries of shared libraries
and manipulate the RPATH and DT_NEEDED entries of executables and libraries.

Run `patchelfmod --help` or see the manpage (`man patchelfmod`) for more information.


**Installation:**<br>
```
./bootstrap.sh
./configure
make check strip
make install
```


**Homepage:** https://github.com/darealshinji/patchelfmod

**Ubuntu packages:** https://launchpad.net/~djcj/+archive/ubuntu/tools/+packages?field.name_filter=patchelfmod


**License:**<br>
Copyright (c) 2004-2014 Eelco Dolstra <eelco.dolstra@logicblox.com>,
              2014      djcj <djcj@gmx.de>

Contributors: Zack Weinberg, vdanjean, rgcjonas, Jeremy Sanders, Thomas Tuegel,
              Changli Gao

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or (at
your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
