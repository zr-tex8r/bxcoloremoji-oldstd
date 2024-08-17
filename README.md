bxcoloremoji-oldstd Bundle
==========================

LaTeX: Image files that were standard in old bxcoloremoji

Overview
--------

This is the image set that was used in the default settings of the
[bxcoloremoji package] of version 0.x.

It is now provided as custom image sets of the new bxcoloremoji.

  - `twemoji-pdf`: PDF image that is converted from SVG image data of
    [twemoji].
  - `twemoji-png`: 72-pixel PNG image of twemoji.

### Installation

  - Move `twemoji-pdf` and `twemoji-png` directories into the location
    `$TEXMF/tex/latex/bxcoloremoji-oldstd`.

### License

Graphics work is licenced under:

CC-BY 4.0: (https://creativecommons.org/licenses/by/4.0/)  
Copyright Twitter, Inc and other contributors


Usage
-----

You can use these image sets using hte `custom` parameter.

    \usepackage[custom=twemoji-pdf]{bxcoloremoji}% use twemoji-pdf set
    \usepackage[custom=twemoji-png]{bxcoloremoji}% use twemoji-png set

NB. For compatibility with v0.x, you can omit `custom=` and simply write
`twemoji-pdf` or `twemoji-png`. But you are encouraged to use the newer
form.


Revision History
----------------

  * Version 1.0   〈2024/08/18〉
      - The first public veresion.
      - The image data is the same as that of [bxcoloremoji package]
        version 0.14.

[bxcoloremoji package]: https://github.com/zr-tex8r/BXcoloremoji
[twemojis package]: https://ctan.org/pkg/twemojis

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
