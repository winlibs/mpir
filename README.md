MPIR is built using VC9 projects files. No patch are necessary but to rename the library to mpir_a.lib. Follow the instructions in the readme.txt in the MPIR sources and build “lib_mpir_p4” to get the static library we use for PHP.
 
To build an ASM optimized version, you will have to install Yasm assembler (http://www.tortall.net/projects/yasm/). Complete instructions are available under http://www.tortall.net/projects/yasm/wiki/VisualStudio2005 .
 
The modified sources (only renamed the mpir.lib in lib_mpir_gc to mpir_a.lib) is available under https://github.com/winlibs/mpir .
 