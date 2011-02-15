Contemplate
===========

Sensible Adobe® Photoshop® templates, so you don't have to think about it.

This project is a work in progress (and most likely always will be). The documentation especially so.

A note on graphic templates on today's Web: As we outsource a lot of our distribution channels to companies and applications like Facebook and the iTunes App Store, we have less control over their appearance than ever. Our graphics *will* be resized in many ways and in many future ways we can't yet predict. It may be more reasonable to create generally good graphics that do not have exact one-pixel embosses as a form of future proofing. This is a choice I leave to you.

Web
---

The "wow" file is in web/webpage.psd.

Apple: Icons
------------

Devices with different resolutions will need different [media query](http://www.w3.org/TR/css3-mediaqueries/) settings in your HTML for the appropriate icon.

    <link rel="apple-touch-icon" type="image/png" media="screen and (resolution: 163dpi)" href="/img/apple-icon-57x57.png">
    <link rel="apple-touch-icon" type="image/png" media="screen and (resolution: 132dpi)" href="/img/apple-icon-72x72.png">
    <link rel="apple-touch-icon" type="image/png" media="screen and (resolution: 326dpi)" href="/img/apple-icon-114x114.png">

*Please* turn off the Apple Gloss group and disable the Icon group's vector mask when you save your icon. Apple will apply these effects for you; the idea is that the gloss and vector mask act to *preview* how the icon will look so you can make adjustments as necessary. I can't guarantee that these effects are identical to Apple's (because I painstakingly reverse engineered them), but I stand behind them and their resolution-independent vector shape/mask goodness.

For more icon references, please visit:

- [Jon Hicks's Icon Reference](http://hicksdesign.co.uk/iconreference/)
- [Apple Human Interface Guidelines: Icons](http://developer.apple.com/library/ios/#documentation/userexperience/conceptual/mobilehig/IconsImages/IconsImages.html)

If you're submitting an app to the App Store, you'll want to use the 512x512 icon, because it's required, and iOS will resize it in all other references; however, you can customize each icon if you so prefer, like [The Incident](http://itunes.apple.com/us/app/the-incident/id385533456).

Apple: App Store screenshots
-----------------------------------

The App Store on the iPhone, iPad, and the desktop will resize your artwork slightly for white borders, killing any pixel-perfect expectations. Be wary about what your text could possibly look like on the iPhone (resized to about 70%). Your artwork will resize as follows:

- iPhone App Store
    - iPhone app page
        - Portrait: 277x340
        - Landscape: (App Store doesn't rotate orientation on iPhone)
    - iPad app page
        - Portrait: (Can't download iPad apps on iPhone)
        - Landscape: (Can't download iPad apps on iPhone)
- iPad App Store
    - iPhone app page
        - Portrait: 308x464
        - Landscape: 464x308
    - iPad app page
        - Portrait: 358x478
        - Landscape: 478x358
- Desktop App Store
    - iPhone app page
        - Portrait: 318x478
        - Landscape: 478x318
    - iPad app page
        - Portrait: 358x377
        - Landscape: 480x360 (Not sure why this is full)
  
The App Store on the iPhone doesn't rotate based on orientation, and so landscape screenshots won't orient correctly. I don't recommend landscape screenshots for iPhone-specific apps, unless the screenshot experience would be diminished by sticking to a portrait screenshot, e.g. [Angry Birds](http://itunes.apple.com/us/app/angry-birds/id343200656) or some other landscape-heavy app.

Apple: PR
---------

Proper transparent RGB versions of [Apple's PR product info images](http://www.apple.com/pr/products/). Apple's images are merged CMYK TIFF files and are thus typically difficult or unsuitable to use.

Apple: Teehan+Lax
-----------------

The mockups of the iPhone, iPhone 4, and iPad are stripped-down versions of the gorgeous Teehan+Lax mockups, convenient if you just need a quick mockup of the front of the device. All proper credit and thanks goes to them, and I make no illusions of ownership or otherwise. Please visit their website to download the full versions and donate if you can. 

- [iPhone 4](http://www.teehanlax.com/blog/2010/06/14/iphone-gui-psd-v4/)
- [iPhone 4 Retina Display](http://www.teehanlax.com/blog/2010/08/12/iphone-4-gui-psd-retina-display/)
- [iPad](http://www.teehanlax.com/blog/2010/02/01/ipad-gui-psd/)

Favicon
-------

I suggest [Telegraphics's free plugins](http://www.telegraphics.com.au/sw/) for favicon.ico creation. Specifically, use the "Ico (Windows icon) format" plugin to create individual .ico files, then highlight and drag all of them on top of the "Icobundle Utility," which will create a single .ico file of various resolutions.

Facebook
--------

The maximum size of the Facebook Page image is 180x540.

The [Open Graph image](http://developers.facebook.com/docs/opengraph) minimum size is 50x50 and has a maximum aspect ratio of 3:1. That means the widest image is 150 pixels if the minimum height is respected at 50 pixels, and the tallest image is 150 pixels if the minimum width is respected at 50 pixels. I couldn't find information on the image's maximum size, but I suspect Facebook doesn't want to encourage images to be prematurely sized for a website that is constantly in flux, but rather provide general guidelines and let Facebook create optimized images as needs change.

    <meta property="og:image" content="http://www.example.com/open_graph.jpg">

Twitter
-------

Because Twitter centers its background, creating a good background image is difficult in a static document. The Twitter template shows what the center content column would look like on different screen resolutions. The old Twitter design offers between 19 and 259 pixels for a design visible next to the center content column, and the new Twitter design, which uses a max-width, offers between 52 to 120 pixels visible.

PayPal
------

Templates for [co-branding the PayPal Checkout pages](https://cms.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=developer/e_howto_html_ProfileAndTools#id08A9E8005PM). Also see [Yahoo's take](http://help.yahoo.com/l/us/yahoo/smallbusiness/store/order/paypal/paypal-08.html) on it.

License
-------

This work is licensed under the [Creative Commons Attribution license](http://creativecommons.org/licenses/by/3.0/).

Authors
-------

Richard Cornish  
[www.richardcornish.com](http://wwww.richardcornish.com)  
[rich@richardcornish.com](mailto:rich@richardcornish.com)