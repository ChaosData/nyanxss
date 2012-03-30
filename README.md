An all-in-one flashy XSS payload/"neat JS app."

How to use it
-------------

`<script type="text/javascript" src="http://example.com/nyan.js" charset="utf-8"></script>`

`executepayload(20,"XSS!")`

After the script is loaded, a call to `executepayload` will set everything in motion. The first argument will set the number of nyan cats flying around and the second argument will set the message that is displayed.

These default to 80 and "YOU HAVE BEEN OWNED!", respectively.

If, however, you do not want to display a message, pass an empty string to `executepayload`:

`executepayload(100,'')`

Supported Browsers
------------------

* Currently:
  *  Mozilla Firefox
  *  Google Chrome

* Planned:
  *  Opera
  *  Internet Explorer 9/10
