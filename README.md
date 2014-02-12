A place for Mozilla to track our Cordova work. All of the plugins are
submodules that point to the real repository hosted by Apache. If you
want to use the most up-to-date version of a plugin (with fixes that
may not be released), use the github URL and specify the dev branch:

$ `cordova plugin add https://github.com/apache/cordova-plugins-camera.git#dev`

If you just need the latest released version, just simply do `cordova
plugin add org.apache.cordova.camera`. Replace "camera" with any of
the plugins below.

To contribute, fork any of the plugin repos and open PRs. It's best to
let us know if you do that, by opening an issue here, or contact us in
#apps on irc.mozilla.org.

Plugin Status (see the individual plugin docs for details):

* camera - partial (many of the settings are ignore)
* contacts - partial (read-only)
* device - partial (most device properties are null)
* device-motion - full (needs to be confirmed)
* device-orientation - mostly (one option is ignored)
* geolocation - full
* vibration - full

Missing plugins:

* battery status
* filesystem
* file transfer
* globalization
* in app browser
* media
* media capture
* network information
* splash screen
