## AnalyticsEventGenerator Sample - iOS App

This is a sample library
using [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary)
via Swift Package Manager.

In order to access the private SPM artifact produced
from [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary)
we need to update `~/.netrc` file:

```
machine github.com
login YOUR_LOGIN
password YOUR_PERSON_ACCESS_TOKEN

machine api.github.com
login YOUR_LOGIN
password YOUR_PERSON_ACCESS_TOKEN

machine maven.pkg.github.com
login YOUR_LOGIN
password YOUR_PERSON_ACCESS_TOKEN
```

**Make sure `YOUR_PERSON_ACCESS_TOKEN` has `read:packages` permission!**

To build using a locally build version
of [AnalyticsEventGeneratorSample-SharedLibrary](https://github.com/zawadz88/AnalyticsEventGeneratorSample-SharedLibrary)
please follow the steps described in [KMMBridge docs](https://kmmbridge.touchlab.co/docs/spm/IOS_LOCAL_DEV_SPM).
