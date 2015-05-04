## How this application works? ##

All the programming is made with PHP. You may change or optimize PHP code if you need to.
You need to have primary key in MySQL tables if you want to change database tables.

When you are inserting a new row, the application will insert the next biggest number in your primary key or if you don’t have numbers like primary key will insert auto generated GUID.

Supports PHP 4 and PHP5

We use some external libraries and applications:

HTML Purifier for preventing xss attacks and cleaning HTML code
TinyMCE  changes all text areas into user friendly HTML editor permitting your user to write basic HTML (only some HTML tags are enabled). You can personalize TinyMCE! Or if you don’t need that just delete the TinyMCE folder.

And Tables table sorter(  http://tablesorter.com/docs/ ) jquery plug-in for better table output.