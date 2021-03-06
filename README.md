stb
===

single-file public domain libraries for C/C++

library | description
--------- | ---------
**stb_image.c**       | image loading/decoding from disk/memory: JPG, PNG, TGA, BMP, PSD, GIF, HDR, PIC
**stb_vorbis.c**      | decode ogg vorbis files from memory to float/16-bit signed output
**stb_truetype.h**    | parse, decode, and rasterize characters from truetype fonts
**stb_image_write.h** | image writing to disk
**stb.h**             | helper functions for C, mostly redundant in C++
**stb_c_lexer.h**     | simplify writing parsers for C-like languages
**stb_perlin.h**      | revised Perlin noise (3D input, 1D output)
**stb_textedit.h**    | guts of a text editor for games etc implementing them from scratch

FAQ
---

#### What's the license?

These libraries are in the public domain (or the equivalent where that is not
possible). You can do anything you want with them. You have no legal obligation
to do anything else, although I appreciate attribution.

#### If I wrap an stb library in a new library, does the new library have to be public domain?

No.

#### A lot of these libraries seem redundant to existing open source libraries. Are they better somehow?

Generally they're only better in that they're easier to integrate,
easier to use, and easier to release (single file; good API; no
attribution requirement). They may be less featureful, slower,
and/or use more memory. If you're already using an equivalent
library, there's probably no good reason to switch.

#### Will you add more image types to stb_image.c?

If people submit them, I generally add them, but the goal of stb_image
is less for applications like image viewer apps (which need to support
every type of image under the sun) and more for things like games which
can choose what images to use, so I may decline to add them if they're
too rare or if the size of implementation vs. apparent benefit is too low.

#### Are there other single-file public-domain libraries out there?

Yes. I'll put a list here when people remind me what they are.


