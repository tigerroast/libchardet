# libchardet
Mozilla's Universal Charset Detector C/C++ API

Installation instructions:
-download tarball and extract into a directory on /home/user, like (for example) /home/user/libchardet.
-either navigate to package directory in a CLI shell with (for example) "cd ~/libchardet," or with Dolphin.
-run (in the shell or in Dolphin by pressing "F4") "makepkg -si."

All dependencies (bash, gcc-libs) are in the official repositories. The -si flag will automatically fetch those dependencies if they're not already installed and install them and the package once everything finishes building. Ain't automation sweet? :)

Source: http://ftp.oops.org/pub/oops/libchardet/

PKGBUILD ported from the AUR: https://aur.archlinux.org/packages/libchardet/
