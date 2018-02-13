# MediaRouter

This sample app shows how to use Android's MediaRouter to add a Cast button to a Google Cast sender app. There are 3 ways to add a Cast button: MediaRouterActionProvider, MediaRouteButton or a custom button.
Note this sample app does not control a Google Cast device like Chromecast; it is only meant to show how to add a Cast button to an Android app.

## Dependencies
* The Android SDK android-support-v7-appcompat and android-support-v7-mediarouter support libraries (at least revision 19).
* The Android SDK google-play-services_lib library (at least version 4.2.34)

## Setup Instructions
* Get a Chromecast device and get it set up for development: https://developers.google.com/cast/docs/developers#Get_started
* Register an application on the Developers Console (http://cast.google.com/publish). Select the Custom Receiver option and specify the URL to where you are hosting the receiver/receiver.html file (You can use Google Drive to host your files: https://googledrive.com/host/0B716ywBKT84AMXBENXlnYmJISlE/GoogleDriveHosting.html). You will get an App ID when you finish registering your application.
* Setup the project dependencies
* Insert your App ID in the strings.xml in the res directory of the project (look for app_id in that file)
* Compile and deploy to your Android device.

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs
* Design Checklist (http://developers.google.com/cast/docs/design_checklist)
* If you find any issues, please open a bug here on GitHub

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/) and the [Google Cast SDK Additional Developer Terms of Service](https://developers.google.com/cast/docs/terms/).

## Google+
Google Cast Developers Community on Google+ [http://goo.gl/TPLDxj](http://goo.gl/TPLDxj)
