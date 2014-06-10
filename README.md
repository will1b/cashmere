cashmere
========

Successor for ['Modern TweetDeck'](https://github.com/pixeldesu/modern-tweetdeck) built with LESS

**WARNING:** This modification cannot be applied directly *without* a plugin for your browser that allows userstyles on certain webpages. I would recommend [Stylish/userstyles.org](http://userstyles.org/).

## Requirements

* Any browser that is not Internet Explorer, *I highly doubt it will work there.*
* A plugin that provides support for userstyles

## Installation

These instructions are for Stylish on [Chromium-based browsers (like Chrome)](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [Mozilla-based browsers (like Firefox)](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). Steps will vary based on browser and plugin.

### How to add a new style

* Click on the Stylish icon.
* Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
* Click on "Write New Style"

### How to install this style

* Name the Style anything you want, but something easy to recognise like *Cashmere* would be good.
* Paste the text from `cashmere.css` for the theme you use on the [releases page](https://github.com/pixeldesu/cashmere/releases) into the textbox, below the `@moz-document...` line if you have one.
* Click on **Save** and look at TweetDeck!

## Chrome

* Create a rule pointing to `URLs starting with` `https://tweetdeck.twitter.com`.

## Firefox

* Add the following into the textbox, on a single line: 
* `@-moz-document url-prefix("https://tweetdeck.twitter.com") {` and paste the text from `cashmere.css` after that.
* Scroll to the bottom of the textbox and add an extra line with a single `}` on it.

### How to use a custom loading image

Follow the above steps, but open the theme in Stylish afterwards and do the following:

* Upload your image to a host where it will stay up permanently
* Copy the URL and paste it into the line starting `background-image: url(` where the default URL is.
* Click on save.
* Notice the changes on refresh!