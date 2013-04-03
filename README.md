modernizr-ie
============

Modernizr test to check the version of Internet Explorer.

If the test detects Internet Explorer, Modernizr.ie will be set to the
version. Also, the HTML element will be given a classname of "ie" and
"ie#" where # is the version number (for example, "ie8"). If the test
doesn't detect Internet Explorer, Modernizr.ie will be set to false and 
no classes will be added.

This test doesn't use Modernizr's API, but the clever guys at Modernizr
probably wouldn't approve of a non-feature-detecting test anyway!
