## AnalyticsEventGenerator Sample - iOS App

You need to have XCode and Cocoapods installed.

For now using
locally-built [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary)
pod is supported. You need to follow these steps:

- build the library in AnalyticsEventGeneratorSample-SharedLibrary with `./gradlew assemble`
- install pod in `AnalyticsEventGeneratorSample-iOSApp` via `pod install`
- open in XCode via `SampleiOSApp.xcworkspace` so that Cocoapods works as expected
