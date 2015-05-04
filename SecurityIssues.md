## Security issues ##

For security reason change your folder name.

For security reasons deleting is not allowed.

Change the $key inside cookie.php and setcookie.php (It is the same key).

Don’t put direct link to your application from your web site (we don’t what search engines to know about our application).

Change the folder name give some strange name (e.g  3A8ahupu\_MySQL\_Lite\_Administrator).

Don’t give root access to your client. Make new profile with only select, insert and update. You may also limit access to some database tables.

This application uses cookie and session for authentication.

The cookies are encrypted with MCRYPT\_RIJNDAEL\_256 and MCRYPT\_RIJNDAEL\_128 algorithm.(you may need php\_mcrypt module)

All the pages have “Do not follow” for the search engines.