## AnalyticsEventGenerator Sample - iOS App

You need to have XCode and Cocoapods installed.

This
uses [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary).
The spec for this library is published
to [AnalyticsEventGeneratorSample-Specs](https://github.com/zawadz88/AnalyticsEventGeneratorSample-Specs).

To run locally:

- make sure you're using
  an [SSH key with Git](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- execute `pod install`
- open in XCode via `SampleiOSApp.xcworkspace` so that Cocoapods works as expected (or run through Fleet)

You can also build with a locally checked
out [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary).
To do so:

- build the library in AnalyticsEventGeneratorSample-SharedLibrary with `./gradlew assemble`
<<<<<<< HEAD
- install pod in `AnalyticsEventGeneratorSample-iOSApp` via `pod install`
- open in XCode via `SampleiOSApp.xcworkspace` so that Cocoapods works as expected
=======
- edit `AnalyticsEventGeneratorSample-iOSApp/Podfile` and replace the Pod location to a local one as suggested in that
  file
- update pods via `pod update`
- open in XCode via `SampleiOSApp.xcworkspace` so that Cocoapods works as expected (or run through Fleet)
>>>>>>> d61786c (set up with remote pod)
