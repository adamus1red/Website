# StrathTech.co.uk

This is the site for [StrathTech](http://www.strathtech.co.uk/). New layouts and designs are tested here before being deployed on the main site.

It uses [bootstrap](https://github.com/twitter/bootstrap), [jekyll][jk], [ruby][rb], and [liquid](https://github.com/Shopify/liquid/)

[![build status](https://ci.gitlab.strathtech.co.uk/projects/7/status.png?ref=master)](https://ci.gitlab.strathtech.co.uk/projects/7?ref=master)

Requirements
------------

Development time dependencies:

* [Ruby][rb]
* [Gems][gm]
* [Jekyll][jk]
* [Rdiscount][rd] (optional - comment out in `_confing.yaml` to use Maroku)
* [Node.js][no] & [Grunt.js][gr] (optional - only if you wish to use GruntJS)

Run-time dependencies:

* A web server (any will do, including that Java one smeed made us do in 3rd year)


Complete Idiot's Guide
----------------------

To use this template:

1. Clone to some directory
* Modify `_config.yaml` with your name, blog title, description and etc...
* Tweak HTML files in `_layouts` to personalize.
* Create blog entries in `_posts/` - work off the sample posts there
* Run `jekyll --server` to generate site locally
* View it by going to `http://localhost:4000` and make sure it looks good
* If all is well, upload contents of `_site` to your server
* Repeat steps 4-7 to update blog

Features
--------

Following features are available:

* Automatically generate a valid RSS feed (see feed.xml in root directory).
* Automatically generate a valid Google Sitemap (see sitemap.xml in root directory).
* Automatically generate a .htaccess file with error 404 & 500 support
* Automatically generate committee list using a dataset

Credits
-------

Based off of [Bootstrap](http://getbootstrap.org/)

All other content, edits & code are by [StrathTech Web team][ss-wt]


Licence
-------

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">StrathTech Website</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://strathtech.co.uk" property="cc:attributionName" rel="cc:attributionURL">StrathTech</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="http://strathtech.co.uk/contact.html" rel="cc:morePermissions">http://strathtech.co.uk/contact.html</a>.

[rb]: http://www.ruby-lang.org/
[gm]: http://rubygems.org/
[jk]: https://github.com/mojombo/jekyll
[rd]: https://github.com/rtomayko/rdiscount/
[dp]: http://recursive-design.com
[gr]: http://gruntjs.com
[no]: http://nodejs.com
[cc-l]: http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png
[ss-c]: http://strathtech.co.uk/contact
[ss-wt]: http://gitlab.strathtech.co.uk/Society/website/