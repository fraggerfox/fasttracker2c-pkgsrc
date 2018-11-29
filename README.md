ft2clone-pkgsrc
===============

NetBSD pkgsrc script for Fasttracker II clone.

You can find Fasttracker II clone [here][1]

Installation
------------

Copy `audio/ft2clone` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any package.

`$ cd /usr/pkgsrc/audio/ft2clone`<br>
`$ make install clean`

For a list of dependencies for the build check [here][1]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* The Dual-Screen PDF Viewer was originally written by [Olav Sørensen][3]

License
-------

BSD 2-clause. See LICENSE.

[1]: https://16-bits.org/ft2.php
[2]: https://twitter.com/8bitbubsy

