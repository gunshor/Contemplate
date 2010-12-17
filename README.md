Contemplate
===========

Sensible Photoshop templates, so you don't have to think about it. This project is a work in progress (and most likely always will be). The documentation especially so.

Web
---

The "wow" file is in web/webpage.psd.

Apple (App Store screenshots)
-----------------------------
The App Store on the iPhone, iPad, and the desktop will resize your artwork slightly for white borders. Be wary about what your text could possibly look like on the iPhone (resized at about 70%). Don't expect pixel perfection. Your artwork will resize as follows:

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
        - Portrait: 318x477
        - Landscape: 478x318
    - iPad app page
        - Portrait: 358x377
        - Landscape: 480x360
  
The App Store on the iPhone doesn't rotate based on orientation, and so landscape screenshots won't orient correctly. I don't recommend landscape screenshots for iPhone-specific apps, unless the screenshot experience would be diminished by sticking to a portrait screenshot, e.g. Angry Birds.

Favicon
-------

I suggest [Telegraphics's free plugins](http://www.telegraphics.com.au/sw/) for favicon.ico creation. Specifically, use the "Ico (Windows icon) format" plugin to create individual .ico files, then highlight and drag all of them on top of the "Icobundle Utility," which will create a single .ico file of various resolutions.

Facebook
--------

The maximum size of the Facebook Page image is 200x600.

The [Open Graph image](http://developers.facebook.com/docs/opengraph) minimum size is 50x50 and has a maximum aspect ratio of 3:1. That means the widest image is 150 pixels if the minimum height is respected at 50 pixels, and the tallest image is 150 pixels if the minimum width is respected at 50 pixels. I couldn't find information on the image's maximum size, but I suspect Facebook doesn't want to encourage images to be prematurely sized for a website that is constantly in flux, but rather provide general guidelines and let Facebook create optimized images as needs change.

    <meta property="og:image" content="http://www.example.com/open_graph.jpg">

License
-------

This work is licensed under the [Creative Commons Attribution license](http://creativecommons.org/licenses/by/3.0/).

Authors
-------

Richard Cornish  
[www.richardcornish.com](http://wwww.richardcornish.com)  
[rich@richardcornish.com](mailto:rich@richardcornish.com)