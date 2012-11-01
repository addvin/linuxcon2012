Image Sizing
=============

Images should fit within a 600x900 area to best display
with the reveal.js theme.  A quick way to do this is to
use ImageMagick to convert all your images that are too
large:

    mogrify -resize 600x900\> *.png
