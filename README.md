simplisafe-ios
==============

A very basic iOS application to control your SimplSafe alarm system

*Note: This is not affiliated with SimpliSafe in any way. It's just a hobby project for my personal use and I'm sharing in case someone else is interested.*


**Background**

I am very unsatisfied with the application that SimpliSafe offers (it's just a mobile web page wrapped in Cordova) so I wrote a bare-bones native client.

**Operation**

SimpliSafe does not offern an API, so I proxied the calls that are made and recreated them in AFNetworking.

**Limitations**

Since I don't have multiple locations, I haven't added support for this. Currently, you have to known your information and put it into the settings to work. If there is interest, let me know and I can look at automating this.

**Screenshots**

![ScreenShot](https://raw.github.com/greencoder/simplisafe-ios/master/Screenshots/settings.png)

![ScreenShot](https://raw.github.com/greencoder/simplisafe-ios/master/Screenshots/dashboard.png)