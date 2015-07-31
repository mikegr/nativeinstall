Native App install banners
==========================

Native App install banners are similar to Web app install banners, 
but instead of adding to the Homescreen will let the user inline install your native app.
Chrome will decide when to first prompt the user to install the app, 
currently when the user has visited your site twice over two separate days during the course of two weeks.

Documentation 
https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android#native

How to integrate for George Go
------------------------------

* Add in the head section a link to the manifest file `<link rel="manifest" href="/manifest.json">`
* Add the [Manifest file](https://github.com/mikegr/nativeinstall/blob/gh-pages/manifest.json)
* Add the four icons. 

[Icon1](https://github.com/mikegr/nativeinstall/blob/gh-pages/george_launcher.png)
[Icon2x](https://github.com/mikegr/nativeinstall/blob/gh-pages/george_launcher-2x.png)
[Icon3x](https://github.com/mikegr/nativeinstall/blob/gh-pages/george_launcher-3x.png)
[Icon4x](https://github.com/mikegr/nativeinstall/blob/gh-pages/george_launcher-4x.png)


Requirements to test
--------------------

* Chrome 44+ (Latest version of Chrome from the Play Store is sufficient)
* "George Go" app MUST NOT be installed
* Activate flag in Chrome: chrome://flags/#bypass-app-banner-engagement-checks
* Access via HTTPS is important!

Go to 
https://mikegr.github.io/nativeinstall
for a working Georg Go example 

Screenshots
-----------
![Native App Install Banner](screenshots/screen1.png "Banner")
![Native Install Dialog](screenshots/screen1.png "Native Install Dialog")

Another example from the Chrome developers
https://github.com/GoogleChrome/samples/blob/gh-pages/app-install-banner/related-applications/manifest.json
