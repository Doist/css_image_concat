css_image_concat
===========================================

A script that can concat images into one image and create a CSS file.
Super useful when you want decrase issuing a lot of HTTP requests
due to a lot of small images (like icons).

To install it do following::

    sudo pip install css_image_concat

This script takes three inputs::

    image_dir: A directory of images
    out_img: An output path to the concated image
    out_css: An output path to a CSS file

Usage is::

    css_image_concat <image_dir> <out_img> <out_css>

It will then process all the images of `image_dir` and create one
image and one CSS file with classes. The CSS classes have following name::

    cmp_<filename>

This script requires ImageMagick ( http://imagemagick.org/ )

More info at http://amix.dk/blog/post/19682#css-image-concat

Copyright by Amir Salihefendic ( http://amix.dk/ )
License MIT
