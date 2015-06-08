![screenshot](https://raw.githubusercontent.com/eface2face/iosrtc-apprtc/master/art/iosrtc-apprtc.jpg)


# iosrtc-apprtc

Google's [AppRTC](https://github.com/webrtc/apprtc) running in Cordova iOS with HTML5 and [cordova-plugin-iosrtc](https://github.com/eface2face/cordova-plugin-iosrtc).

This project takes the HTML5 version of the [AppRTC](https://apprtc.appspot.com/) applications and runs it in Cordova iOS (iPhone, iPad...) by using the [cordova-plugin-iosrtc](https://github.com/eface2face/cordova-plugin-iosrtc). There are minor changes in the original HTML, JavaScript and CSS in order to make it work as a Cordova application.


## Building

Get the source code and add the Cordova iOS platform:

```bash
$ cordova platform add ios
```

Then install the *cordova-plugin-iosrtc*:

```bash
$ cordova plugin add com.eface2face.iosrtc
```

And run as usual.


## Usage

Once running, enter the same room as one already created via web browser at https://apprtc.appspot.com/, and enjoy!
