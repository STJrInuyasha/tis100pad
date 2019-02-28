# tis100pad
A web site for uploading and sharing solutions for the game TIS-100. This repo is a dated fork of the original, however the original owner seems to have disappeared.

This repo does not reflect the actual directory structure of the original tis100pad site. If you attempt to run this site on your own server, you can put the .py files anywhere as long as your web server is able to execute them. Needless to say I recommend putting them somewhere externally inaccessible.

The original owner used mod_wsgi on an Apache server, but it should work fine with any server setup that can run Flask apps, so long as the appropriate POST requests are correctly routed to the app.

You would also need to initialize your own SQLite database with table, as the code in this repo does not do this for you.
