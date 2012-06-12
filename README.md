ie7-js
======

A JavaScript library to make MSIE behave like a standards-compliant browser.

http://code.google.com/p/ie7-js/

The origin branch is copied from SVN - http://code.google.com/p/ie7-js/source/checkout

In the master branch, I have stripped down the code to only contain the css fixes. You can find the similar stuff in https://github.com/Integralist/Dean-Edwards--IE-7-and-8-and-9

Also, I changed it to load css files asynchronously so that it does not block the js code. This fixed the notable performance issue for me.