# uberw3m

A w3mimgdisplay emulator for ueberzug.

Use by prepending `uberwrap` to your application's command-line, and
configure the application such that instead of running `w3mimgdisplay`,
it runs the `uberw3m` script in this repository. (Installing a symlink
will not work, because uberw3m needs to be able to run the original
w3mimgdisplay in certain situations.)

uberw3m tries to implement the w3mimgdisplay protocol as documented by
this blog post: <https://blog.z3bra.org/2014/01/images-in-terminal.html>

## Copyright

Copyright © 2020 Ash Holland. Licensed under the EUPL (1.2 or later).
