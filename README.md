cordova-plugin-share
====================

Cordova Plugin to open native "share" popup in Android and iOS

### Install

In your phonegap/cordova project, type:

`cordova plugins add https://github.com/markmarijnissen/cordova-plugin-share.git`

### Usage

`navigator.share(text,title,mimetype)`

* text: Text to share, i.e. "Incredible plugin"
* title: Title of popup, i.e. "Share this quote" (android only, default: "Share")
* mimetype: Mimetype, i.e. "image/jpeg" (android only, default: "plain/text")

### More info

* iOS share code from [stack overflow](http://stackoverflow.com/questions/12546574/using-apple-icons-with-ios-6)
* Android share code from [here](http://developer.android.com/training/sharing/send.html). Read if you want to understand *mimetype* options.

### License

MIT license

### Useful?

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/nl_NL/i/scr/pixel.gif" width="1" height="1">
</form>
