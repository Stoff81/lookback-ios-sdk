Lookback SDK for iOS
===========

Lookback is a tool and library for user experience testing that you can install into your app. Lookback records the iOS screen, the front-facing camera, microphone, metadata, touches and active views, and uploads it all in near-realtime to lookback.io where you can study and dive into the data.

Some use cases are:

* Remote research. Invite testers to test your app with just a
  Participate link, and no additional setp.
* User testing sessions. Instead of mounting web cams in your
  testing lab to record both the screen and your tester's
  reactions, let Lookback do the hard work for you.
* Long-term usability study. Let a user record a week of
  using your app, and study trends, reactions and recurring
  problems.

For more examples, see [the Lookback example videos site](http://lookback.io/examples).

## Installation

### Getting Lookback into your app

The easiest way to add the Lookback SDK into your app is to use the [CocoaPods package manager](http://cocoapods.org). After setting up CocoaPods for your project, just add the following line to your Podfile:

    pod 'Lookback'

and run `pod install`.

If you would rather download the .framework and link to it manually, see the [manual installation guide online](http://lookback.io/docs/install-using-cocoapods).

### Setting up Lookback

Please see http://success.lookback.io/installing-the-ios-sdk/configuring-lookback/configuring-lookback-participate for detailed
instructions on how to configure Lookback.
