bochs
=====

# Configuring bochs on OS X 10.9.3

FILE: /iodev/hdimage/cdrom_osx.cc
CHANGES MADE:
// Replaced 'cdrom_base' with 'cdrom_base_c' [Line 351]

# INSTRUCTIONS:
// Install the X11 Library
// Configure using "./configure --with-x11"
// "make"

(If you get an error in the cdrom_osx.cc file, replace it with the given file / make the above change.)
