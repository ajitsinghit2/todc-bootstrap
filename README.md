# Overview #

Because I'm a fan of the new Google UI seen in Gmail, Docs, Calendar, etc, I decided to reproduce
the look of these new UI elements for my own personal use.

## Compatibility ##

This is being tested in the latest versions of Chrome, Firefox, and IE8+.

The following projects are specifically designed for use with todc-bootstrap:

* [todc-select2](http://github.com/todc/todc-select2) - Google-themed select menus
* [todc-datepicker](http://github.com/todc/todc-datepicker) - Google-themed datepicker component

## Requirements ##

* [LESS](http://lesscss.org) - for compiling `.less` files into CSS
* [Twitter Bootstrap](http://github.com/twitter/bootstrap) - this will be automatically checked out, if necessary, during the build process


## Building ##

To build the CSS file, simply run `make` from the top-level directory. If necessary, Twitter Bootstrap will be automatically checked out.

The resulting CSS file will be found at `dist/todc-bootstrap.css`.


## Demo ##

http://todc.github.com/todc-bootstrap/index.html


## Acknowledgements ##

Inspired by [Twitter Bootstrap](http://twitter.github.com/bootstrap/) and, of course, Google.
