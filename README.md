Contemplate
===========

Sensible Adobe® Photoshop® templates, so you don't have to think about it.

A note on graphic templates on today's Web: As we outsource a lot of our distribution channels to companies and applications like Facebook and the iTunes App Store, we have less control over their appearance than ever. Our graphics *will* be resized in many ways and in many future ways we can't yet predict. It may be more reasonable to create generally good graphics that do not have exact one-pixel details as a form of future proofing. This is a choice I leave to you.

Web
---

The "wow" file is in web/webpage.psd.

This may undergo a refactor as per the [Golden Grid System](http://goldengridsystem.com/), and the new files that have been created from it. Responsive web design is the future, and it would be detrimential to us to continue designing purely for the rigid desktop. Web designers must start to think in proportion and scale and not in absolute pixels.

Apple: Icons
------------

*Please* turn off the Apple Gloss group and disable the Icon group's vector mask when you save your icon. Apple will apply these effects for you; the idea is that the gloss and vector mask act to *preview* how the icon will look so you can make adjustments as necessary, and doubling the effects again won't look pretty. I can't guarantee that these effects are identical to Apple's (because I painstakingly reverse engineered them), but I stand behind them and their resolution-independent vector mask goodness.

If you would like to use some of the packaged gloss/shade effects but not others (or if you prefer creating your own effects), either turn on the pre-composed setting in your Web app's HTML (`<link rel="apple-touch-icon-precomposed" href="apple-touch-icon-precomposed.png">`) or check the appropriate checkbox when submitting your native app to the App Store. Check out the YouTube and Weather app icons for some beautifully subtle and customized uses of the glare effect.

If you're submitting a native app to the iTunes App Store: You'll want to use the 512x512 icon, because it's required, and iOS will resize it in all other references; however, you can customize each icon for pixel perfection and smaller downloads if you prefer, like [The Incident](http://itunes.apple.com/us/app/the-incident/id385533456) does.

For icon references, please visit:

- [Icon Reference](http://hicksdesign.co.uk/iconreference/) by Jon Hicks
- [Everything you always wanted to know about touch icons](http://mathiasbynens.be/notes/touch-icons) by Mathias Bynens
- [Human Interface Guidelines: Icons](http://developer.apple.com/library/ios/#documentation/userexperience/conceptual/mobilehig/IconsImages/IconsImages.html) by Apple

Apple: Products
---------------

Proper transparent RGB versions of [Apple's PR product info images](http://www.apple.com/pr/products/). Apple's images are merged CMYK TIFF files and are thus typically difficult or unsuitable to use.

If you're curious to know how to size the facing view of the iPhone 4 image (cropped to itself) so that the interior screen becomes 320x480, it's 37.5%. You're welcome.

For proper GUIs of all interface pieces of the iPhone, iPhone 4, and iPad, check out the excellent [Teehan+Lax downloads](http://www.teehanlax.com/downloads/).

Favicon
-------

I suggest [Telegraphics's free plugins](http://www.telegraphics.com.au/sw/) for favicon.ico creation. Specifically, use the "Ico (Windows icon) format" plugin to create individual .ico files, then highlight and drag all of them on top of the "Icobundle Utility," which will create a single .ico file of various resolutions.

Facebook
--------

The Facebook profile and page image's maximum size is 180x540.

The [Open Graph image](http://developers.facebook.com/docs/opengraph) minimum size is 50x50 and has a maximum aspect ratio of 3:1. That means the widest image is 150 pixels if the minimum height is respected at 50 pixels, and the tallest image is 150 pixels if the minimum width is respected at 50 pixels. I couldn't find information on the image's maximum size, but I suspect Facebook doesn't want to encourage images to be prematurely sized for a website that is constantly in flux, but rather provide general guidelines and let Facebook create optimized images as needs change.

    <meta property="og:image" content="http://www.example.com/open_graph.jpg">

Twitter
-------

Because Twitter centers its background image, creating a good background image is difficult in a static document. The Twitter template shows what the center content column would look like on different screen resolutions. The old Twitter design offered between 19 and 259 pixels of visibility next to the center column, and the new Twitter design, which uses a `max-width` in its CSS, offers between 52 to 120 pixels of visibility.

PayPal
------

Templates for [co-branding the PayPal Checkout pages](https://cms.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=developer/e_howto_html_ProfileAndTools#id08A9E8005PM). Also see [Yahoo's take](http://help.yahoo.com/l/us/yahoo/smallbusiness/store/order/paypal/paypal-08.html) on it.

License
-------

This work is licensed under the [Creative Commons Attribution license](http://creativecommons.org/licenses/by/3.0/).

Author
------

Richard Cornish  
[www.richardcornish.com](http://wwww.richardcornish.com)  
[rich@richardcornish.com](mailto:rich@richardcornish.com)