===================
jquery-image-viewer
===================

jquery-image-viewer is a jQuery plugin that makes it easy to create a flexible, 
robust slideshow on your site.

Features include:

* Forward/next buttons (optional).
* Thumbnail navigation (optional).
* Auto-playing of slideshow with configurable delay (optional).
* Ability to override what image shows first.
* Show as many slideshow as you would like on the page with different configurations for each.

This plugin aims to be unobtrusive and loosely coupled so making changes to the 
structure and style of the slideshow without having to mess with the JavaScript 
is easy.

This plugin was primarily designed as a slideshow but since the code is based on 
selectors, you could use it to show slides of text, or a combinations of other 
elements such as text, images, and video. 

Installation
============

1. First put jQuery (1.3.2 or higher) and the jquery-image-viewer file in the 
`<head>` of your page::

    <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.3.2/jquery.min.js"></script>
    <script type="text/javascript" src="../jquery-image-viewer/jquery.image_viewer.js"></script>

You could also place the JavaScript right before the closing `</body>` tag on 
your page, which will cause the scripts to load after the content, speeding up 
the loading of the page.

Note that in a production environment you should use the packed version of the 
file (jquery.image_viewer.pack.js) to decrease loading times.
    
Example
=======

You can view the `index.html` file in the demo folder for an example on how 
to use the plugin.

Usage
=====

A simple example would be::

    $('#slideshow').image_viewer();

More...
=======

As I'm using this in active projects, I will try and keep this code as up to date
as possible and to make sure it is fast and stable.

If you find any bugs or have some feedback go here
http://github.com/danawoodman/jquery-image-viewer/issues and create a case or get in 
touch with me. Any feedback is welcome!

If you use this in your project, send me an email so I can see what 
you did at:

dana (at) danawoodman.com

Enjoy!
