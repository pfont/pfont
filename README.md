# Pfont
This is a free font under [OFL license](http://scripts.sil.org/OFL).
"pfont" is just a codename for this font and is subject of change when we
reach to a consensus about the final name.

# About
Please read [this link](https://github.com/itmard/pfont/blob/master/ABOUT.md).

# Build
We used to use open .ufo standard for the font repo to be able to keep track of
changes happened to indiviual glyphs but to have multiple weights manageable,
for now we've been somehow get forced to use .glyphs single file format.

The good news is glyphs format is easily convertable to .ufo with this
pip package, glyphs2ufo. But this conversion seems to be oneway so we are
not commiting the result of that tool to this repo for now.

We are looking for integrating [fontmake](https://github.com/googlei18n/fontmake)
instead [fontbakery](https://github.com/googlefonts/fontbakery) which we used
before for our automated builds but being compatible with different shaping
engines is on our top priority which our FontBakery builds seems had some
issue with CoreText so we probably will publish the first versions of the
font with the integrated font generator of glyphs app.
