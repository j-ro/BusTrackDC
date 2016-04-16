An app for iOS and Android to find out when your bus, Circulator, streetcar, or train is coming to a stop near you, using WMATA and NextBus prediction data. 

Download at http://bustrackdc.com

Built using:

* Cordova/Phonegap
* HTML/CSS/Javascript
* jQuery/jQuery UI
* Topcoat
* Underscore.js
* jQuery UI Touch Punch
* FastClick
* iScroll
* xml2json.js
* hammer.js
* jQuery listfilter
* xCode
* Google Maps and Places and Directions APIs
* GALocalStorage.js

## Building, Forking, Improving

Please feel free to download, fork, or help this app improve.

This app is built using the Cordova CLI. To build, first install the CLI, then install the android and iOS platforms. Then install these plugins:

* com.JasonRosenbaum.mapkit (see instructions for installation here: https://github.com/j-ro/Cordova-MapKit)
* cordova-plugin-console
* cordova-plugin-device
* cordova-plugin-dialogs
* cordova-plugin-geolocation
* cordova-plugin-splashscreen
* cordova-plugin-whitelist
* cordova.plugins.diagnostic
* ionic-plugin-keyboard

Copy the contents of the BusTrackDC/www folder in this repository into your app's local /www directory. Copy the contents of config.xml file into your project's config.xml (though you'll have to change the package name and things like that).

Finally, use Cordova's build command to build the app, using the www folder in this repository.

You'll need to add your own WMATA, Google Maps, and Google Analytics keys to config.js in the /www/js/ directory to compile a working version. (Get free keys at http://developer.wmata.com/, https://developers.google.com/maps/signup, and https://google.com/analytics.)

## Bugs and Source

Please direct all bug reports or feature requests to the issue tracker.

Source available at https://github.com/j-ro/BusTrackDC

Version 1.8.7

## License

The MIT License (MIT)

Copyright (c) 2016 Jason Rosenbaum

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.