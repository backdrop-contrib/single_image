Single Image Formatter
======================

This module exposes a field formatter that will display one image from a
multi-value image field. It allows the same options as the original image
formatter, plus the possibility of choosing which image to print.

Choose a positive integer to To select which image to display. If the selected
image doesn't exist, a random one will be chosen.

Similar modules
---------------

There is a similar module named `Field multiple limit` which works for all
types of fields (not only images) but takes a different approach.

For fields with a high number of values, this module might be more efficient. It
will not try to render anything that is not needed. The `Field multiple limit`
module will remove the content once has been already been processed.

If you want a formatter that extends with the standard `Image` field formatter,
`Field multiple limit` may be a better choice, since Colorbox (and other modules)
will integrate with it seamlessly.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Select the `Single image` display formatter on any image field, and adjust
  the settings as needed.

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/single_image/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/single_image/issues.

Current Maintainers
-------------------

- [Jen Lampton](https://github.com/jenlampton).
- Seeking co-maintainers

Credits
-------

- Ported to Backdrop CMS by [Jen Lampton](https://github.com/jenlampton).
- Maintained for Drupal by [Federico Jaramillo](https://www.drupal.org/u/jmfederico).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
