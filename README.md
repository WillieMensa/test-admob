testadmob
=========

a test project for cordova plugin admob

it's quite easy to create this project with cordova command line tool:

    cordova create testadmob com.rjfun.testadmob TestAdmob
    cd testadmob
    cordova platform add android
    cordova platform add ios
    cordova plugin add https://github.com/MobileChromeApps/google-play-services.git
    cordova plugin add https://github.com/floatinghotpot/cordova-plugin-admob.git
    mv www www.default
    mkdir www
    cp plugins/com.rjfun.cordova.plugin.admob/test/index.html www/
    cordova build

    ... cordova emulate android/ios, or import the android project into eclipse or ios project into xcode

That's it.

