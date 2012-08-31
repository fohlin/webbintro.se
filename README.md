# An Introduction to Web Development, in Swedish #

This project contains Swedish educational material
for client side web development. It is created and maintained as part of the
course [Introduction to Web Development][DA156A] at [Malmö University][Mah]. The website in this repository is published at <http://webbintro.se/>.

[DA156A]:	http://edu.mah.se/sv/Course/DA156A
[Mah]: 		http://mah.se/english

## Development Note ##

Most documents contain resource paths relative to the server root (starting
with `/`). This means that the site is best tested from a web server. One simple
way to get one running, is issuing the command `python -m SimpleHTTPServer`
(for Python 2) from the `site` directory.

Note that documents include a Google Analytics snippet, which you want to remove or modify for before reuse.

## License ##

All content is available under a [Creative Commons Attribution 2.5 Sweden](http://creativecommons.org/licenses/by/2.5/se/) license. In most cases, this should be equal to the [generic version](http://creativecommons.org/licenses/by/2.5/). Attribution in the form of a link to <http://webbintro.se/> is much appreciated.

The project includes [html5shiv](http://code.google.com/p/html5shiv/)
(`site/js/html5shiv.js`), which is MIT licensed.
