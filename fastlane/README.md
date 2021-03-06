fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios hello
```
fastlane ios hello
```

### ios getTeamNames
```
fastlane ios getTeamNames
```

### ios create_keys
```
fastlane ios create_keys
```

### ios download_keys
```
fastlane ios download_keys
```
Download keys
### ios buildAdHoc
```
fastlane ios buildAdHoc
```
Build Ad Hoc
### ios build
```
fastlane ios build
```
Build
### ios app_center
```
fastlane ios app_center
```
App Center
### ios firebase
```
fastlane ios firebase
```
Deploy to Firebase Distribution
### ios tf
```
fastlane ios tf
```
Upload to TestFlight
### ios tf_external
```
fastlane ios tf_external
```
Upload to Test Flight - External
### ios inc
```
fastlane ios inc
```
Increment Build Number

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
