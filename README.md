## HCE Demo
This project demonstrates the [Cordova Host Card Emulation (HCE) plugin](https://github.com/don/cordova-plugin-hce).

This app reimplements the [Android card emulation example](http://developer.android.com/samples/CardEmulation/index.html) with Cordova and is intended to be used with the [Android card reader example](http://developer.android.com/samples/CardReader/index.html).

For more information, see [cordova-plugin-hce](https://github.com/don/cordova-plugin-hce).

## Installing

    cordova platform add android
    cordova plugin add cordova-plugin-hce --variable AID_FILTER=F222222222
    cordova run --device
