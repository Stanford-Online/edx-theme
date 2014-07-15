Overview
========
This directory stores Stanford's theming files for its edX instance.
We're storing the stuff here and then pulling it in to our instance
when we deploy.

We've organized the tree to mimic the directory structure of the edX
codebase so that it's easy to tell where the files will end up upon
deploy. We'll use a special settings file to set the template and
staticfiles paths properly to point to these files.

Theme Authoring
===============
The proposed theming solution for edX provides a number of hooks for
themes to adjust both HTML and CSS to their liking.


License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.  The copyright for the
Stanford brands and assets (e.g. logo and images) are held by Stanford
University.
