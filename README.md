# What is AMP?
* A subset of html with...
* ... a set of custom html tags
* Limited Javascript and CSS

# Why is AMP?
* Because ads messed up webpages for mobile

# How does AMP work?
* Allow only asynchronous scripts
* Size all resources statically
* Don’t let extension mechanisms block rendering
* Keep all third-party JavaScript out of the critical path
* All CSS must be inline and size-bound
* Font triggering must be efficient
* Minimize style recalculations
* Only run GPU-accelerated animations
* Link between amp and non-amp pages

# Where can I find more information?
Project: https://www.ampproject.org/
Blog: https://googleblog.blogspot.fi/2016/02/amping-up-in-mobile-search.html
TechCrunch: http://techcrunch.com/2016/02/24/wordpress-sites-now-support-googles-amp-to-make-mobile-pages-load-much-faster/


# Quickstart
The history of this repository contains different stages of the site that
can be used to demonstrate how to build an AMP enabled page.

Use the following Python (2.7) command to serve the page:
```
python -m SimpleHTTPServer 8765
```
and open the page in your browser: http://localhost:8765
