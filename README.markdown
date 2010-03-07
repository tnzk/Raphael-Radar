
Raphael Radar 0.0.0
===========================

LAST UPDATED: 2010-03-07

What is this?
--------------

Raphael Radar is a JavaScript library to draw a controlable radar chart
using Raphael.js, a JavaScript library to draw SVG.

A radar chart is also known as a web chart or a spider chart. This chart gives
you a method to make multiple variables easy to see. This will provide a way to
show complex data in simple manner.

This library gives you a way to show the radar chart with SVG and to realize
a cool UI selecting complex parameters.

Requirements
-------------

You have to install the libraries below to use Raphael Radar:

  1. Raphael.js 1.3.1 or later
  2. jQuery 1.4.2 or later

If Raphael Radar does not work for you, please use above version of the libraries.

How To Install
--------------

  1. Download and install Raphael.js and jQuery.
  2. Download and extract the archive to your desired directory

How To Use
----------

  1. Load Raphael.js, jQuery and Raphael Radar with using script tag in the header of your HTML document.
     You must load Raphael Radar after loading Raphael.js, or this probably does not work well.
  2. Put a script tag after a element you want to display a chart on.
  3. Call radar(), a function of Raphael Radar in the script tag. This expects seven arguments to work:

       1.  String: An ID of the element you want to show the chart on.
       2. Integer: A width of the chart
       3. Integer: A height of the chart
       4.   Array: An array storing values of each parameter.
       5.   Array: An array storing human-readable names of each parameter. If you do not want to show labels, set null here.
       6.   Array: An array storing IDs of form fields related each parameter. If you do not want, set null here.
       7. Integer: A max value of parameters. The values of array, 4th argument have to be within the range from 0 to this argument.

    More detailed example is available in index.html or URL below:

      [http://www.tnzk.org/devel/Raphael-Radar/example/](http://www.tnzk.org/devel/Raphael-Radar/example/)

Contact
-------

Feel free to ask or complaint me :)

Developed by: KURAZEKO Kyohe ([@tnzk](http://twitter.com/tnzk)), tnzk.marge'_'gmail.com