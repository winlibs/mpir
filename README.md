
MPIR is built using VC9 projects files. No patch are necessary but to rename
the library to mpir_a.lib. Follow the instructions in the readme.txt in the
MPIR sources and build “lib_mpir_p4” to get the static library we use for PHP.

To build an ASM optimized version, you will have to install
[Yasm](http://www.tortall.net/projects/yasm/) assembler. Complete instructions
are available
[here](http://www.tortall.net/projects/yasm/wiki/VisualStudio2005).
