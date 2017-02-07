[![Build Status](https://travis-ci.org/Dynalon/mdwiki.png?branch=master)](https://travis-ci.org/Dynalon/mdwiki)

This is a modified version of MDwiki with changes to the 0.6.x branch.

## Differences from main repo
* The flatly theme for Bootstrap is the main theme rather than the default, allowing the flatly theme to be used offline.  The default Bootstrap theme can be chosen in navigation.md with 'classic'
* Added a function to basic_skeleton.js which adds target="\_blank" to any links to external domains
* Adds a line to the setPageTitle function which will set the text of the title tag to the text of the opening h1 tag of the page if found.

MDwiki
======

100% static single file CMS/Wiki done purely with client-side Javascript and HTML5.

See http://www.mdwiki.info for more info and documentation.
------


Download
--------

See <https://github.com/Dynalon/mdwiki/releases> for readily precompiled releases.

How to build from source
------------------------

1. Install node.js >= 0.8 and npm (if not included)
2. Clone this repo
3. Install deps:

    npm install

4. Install components

    bower install

    (or if not installed globally)
    ./node_modules/.bin/bower install

5. Build MDwiki

    grunt release

    (or if not installed globally)
    ./node_modules/.bin/grunt release

6. Find the `mdwiki.html` in the `release/` and `dist/` folder



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Dynalon/mdwiki/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

