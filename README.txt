=============================
UNIVERSITY OF CAMBRIDGE
Digital Experience Guidelines
=============================

Thank you for downloading the University of Cambridge Digital Experience Guidelines.
We hope it helps to streamline your web development workflow. Enclosed in this bundle
are the CSS, Javascript and image files needed to build a website using the new Digital
Experience Guidelines.


How to use
----------

You can load up the example files in this bundle using your web browser. Each example
file highlights a key area of the DEG philosophy and design. Once you're familiar with
how a DEG-compliant site should look and feel, you can then copy and adapt the example
files to fit your own website content.

More information and full explanations of all the techniques needed to build a
DEG-compliant site can be found on the project homepage, here:

http://www.cam.ac.uk./deg/


Required media files
--------------------

If you're feeling adventurous, there's nothing stopping you from creating your own CSS
and JS files to build your DEG-compliant site. However, we highly recommend using the
provided media files located in the media/ directory of this bundle. They've all been
well-optimised and tested to give you a quick way of building a high-quality site with
minimum effort.

All of the example files in this bundle use the bundled media files. To use them in your
own project, simply copy the media/ directory to your webserver and link to it in your
HTML <head> element like this:

		<link rel="icon" type="image/png" href="media/img/favicon.png">
		<link rel="stylesheet" href="media/css/uoc.min.css">
		
		<!--[if lt IE 9]>
		    <link rel="stylesheet" href="media/css/ie.min.css"/>
		    <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
		<![endif]-->
		
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
		<script src="media/js/jquery.uoc.min.js"></script>
		
		<script>
		    $.uoc();        
		</script>      
    
Just remember to put in the correct paths to all the DEG media files on your server!


Getting involved
----------------

There are lots of ways to get involved with the DEG. If you've used the guidelines in your
own projects, and want to leave feedback, please leave a comment on the DEG website and
we'll get back to you as soon as possible.

http://www.cam.ac.uk/deg/

If you're a confident web developer, and feel that you have something to contribute to the
DEG, please feel free to fork the project on GitHub to work on your own bug fixes or
improvements. Once you've got something you're happy with, submit a pull request and we'll
review your work for possible inclusion into the DEG itself.

http://github.com/uoc/deg


A final note
------------

It is worth noting that these styles do not automatically make up a finished site design.
They are simply a starting point, ideally for rapid prototyping or as a basis for creating
your own designs. You should not feel constrained by the way we have built the initial
code. These media files are simply a set of tools, and you're free to pick and choose from
them as you wish.

Happy coding! :)

=====================================================================================

Created by University of Cambridge and CottonRendle: http://www.cottonrendle.com
See the official site for more info: http://www.cam.ac.uk/deg/