Internet Research Lab web pages
===============================

These are the web pages used by the BYU Internet Research Lab. You
can see the pages at http://internet.byu.edu.

The pages are built using:

- [Flask](http://flask.pocoo.org/)
- [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/)
- [Twitter Bootstrap](http://twitter.github.io/bootstrap/)

Install
-------

> virtualenv env

> source env/bin/activate

> pip install -r requirements.txt

Run
---

> python app.py

to start a local server with the web pages, and

> python app.py build

to build a static set of pages you can place on any web server.

Upload
------

To upload to a server:

> doit install

Modify the file `dodo.py` as needed.

Copyright
---------

Copyright (c) 2015 BYU Internet Research Lab

Released under the <a
href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US">Creative
Commons Attribution-ShareAlike 3.0 Unported License</a>.
