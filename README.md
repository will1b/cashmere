# technicolour
(_previously known as cashmere_)

A user experience and content-focused userstyle for TweetDeck

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

* Name the Style anything you want, but something easy to recognise like *Technicolour* would be good.
* Paste the text from `technicolour.css` for the theme you use on the [releases page](https://github.com/pixeldesu/technicolour/releases) into the textbox.

#### Chrome

* Create a rule pointing to `URLs starting with` `https://tweetdeck.twitter.com`.
* Click on **Save** and look at TweetDeck!

#### Chrome Web App (Extension)

This is a bit more work and does **NOT** require Stylish

* Download both styles from the [releases page](https://github.com/pixeldesu/technicolour/releases)
* Open your file manager/explorer and navigate to `%UserProfile%\AppData\Local\Google\Chrome\User Data\Default\Extensions\hbdpomandigafcibbmofojjchbcdagbl\`
* Next, click on the folder resembling a version number, and afterwards navigate to `web` and `css`
* Now, open `app-light.css` and `app-dark.css`
* **IMPORTANT STEP:** Don't replace the styles with the one from technicolour, go down 1-2 lines and paste the technicolour-style after the original one.
* Refresh the tab/standalone window with the Chrome Extension, and you now have both styles installed (you can switch them in the settings!)

**NOTE:** You have to do this every time after TweetDeck reloads CSS files after an update!

#### Firefox

* Add the following into the textbox on a single line, before the contents of technicolour.css: 
* `@-moz-document url-prefix("https://tweetdeck.twitter.com") {`
* Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
* Click on **Save** and look at TweetDeck!

### How to use a custom loading image

Follow the above steps, but open the theme in Stylish afterwards and do the following:

* Upload your image to a host where it will stay up permanently
* Copy the URL and paste it into the line starting `background-image: url(` where the default URL is.
* Click on save.
* Notice the changes on refresh!

**Notice:** The new loading image needs to be smaller, so use a 150x150px sized image and it just works fine!