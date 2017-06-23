
<!--#echo json="package.json" key="name" underline="=" -->
twinhelix-iepngfix-pmb
======================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
A clone of TwinHelix&#39;s IE PNG Alpha Fix (iepngfix HTC) repo. This clone
comes with a readme, package manifest and npm package.
<!--/#echo -->

* Cloned from http://git.twinhelix.com/cgit/iepngfix/
  * with minor modifications to better fit my text editor.
* Original readme: http://www.twinhelix.com/css/iepngfix/
  * Couldn't find a license for the readme itself so this one is
    based on [iepngfix.html][howto-html] instead.
* Live demo: [here on Github][howto-html]



What is this?
-------------

This is a IE5.5+ "behavior" that automatically adds near-native PNG
support to MSIE 5.5 and 6.0 without any changes to the HTML document
itself. Supported features include:

* Automatic activation of transparency for PNGs in the page.
* Support for `<img src="">` elements.
* Support for background PNG images (unlike many other scripts!)
* Support for CSS1 background repeat and position (via optional add-on)
* Background images can be defined inline or in external stylesheets.
* Automatically handles changed SRC/background via normal JavaScript
  (e.g. mouseover rollovers) – no special coding needed.
* Change support includes CSS 'className' changes on elements.
* Incorporates automatic workaround for `<a href="">` elements within
  PNG-background elements.
* Tiny script (for fast downloads).
* Licensed under a Free Software license.

How to use
----------

Explained in [iepngfix.html][howto-html].



&nbsp;


[howto-html]: https://mk-pmb.github.io/twinhelix-iepngfix-pmb-js/iepngfix.html


License
-------

&copy; <!--#echo json="package.json" key=".author" -->
Angus Turnbull (http://www.twinhelix.com)
<!--/#echo -->
<!--#echo json="package.json" key=".license" -->
LGPL-2.1+
<!--/#echo -->
