[![Build Status](https://travis-ci.com/tristanheaven/gtkhash.svg?branch=master)](https://travis-ci.com/tristanheaven/gtkhash)
[![Pipeline status](https://gitlab.com/tristanheaven/gtkhash/badges/master/pipeline.svg)](https://gitlab.com/tristanheaven/gtkhash/commits/master)
[![Translation Status](https://hosted.weblate.org/widgets/gtkhash/-/svg-badge.svg)](https://hosted.weblate.org/projects/gtkhash/)

GtkHash
=======

GtkHash is a desktop utility for computing message digests or checksums.
Most well-known hash functions are supported, including MD5, SHA1,
SHA2 (SHA256/SHA512), SHA3 and BLAKE2.

It's designed to be an easy to use, graphical alternative to command-line
tools such as md5sum.

Some interesting features:
* Support for verifying checksum files from sfv, sha256sum, etc.
* Keyed hashing (HMAC)
* Parallel/multi-threaded hash calculation
* Remote file access using GIO/GVfs
* File manager integration
* Small and fast, written in C

Required Dependencies
-------------
* GTK+ 3 or 2
* GLib

Optional Dependencies
---------------------
* Libgcrypt (default)
* libb2 (default)
* Nettle
* OpenSSL
* mbed TLS
* mhash
* Linux Kernel Crypto (AF_ALG)

GtkHash attempts to select the fastest available hash function
implementations at startup. See `./configure --help` for a full list of
options. Build dependencies are not detected implicitly or "automagically".

File Manager Extensions
-----------------------
* Caja (MATE)
* Nautilus (GNOME)
* Nemo (Cinnamon)
* Peony (UKUI)
* Thunar (Xfce)

Licence
-------
GtkHash is free software: you can redistribute it and/or modify it under the
terms of the GNU General Public License as published by the Free Software
Foundation, either version 2 of the License, or (at your option) any later
version.

Translations
------------
![Translation Details](https://hosted.weblate.org/widgets/gtkhash/-/multi-auto.svg)

If you would like to contribute a translation, the easiest way is by using
Weblate:

https://hosted.weblate.org/projects/gtkhash/

Alternatively, updated .po files can be submitted as a Pull Request or Issue on
GitHub:

https://github.com/tristanheaven/gtkhash
