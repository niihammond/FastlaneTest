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
or alternatively using `brew cask install fastlane`

# Available Actions
## Android
### android metadata
```
fastlane android metadata
```
Upload application metadata to Google Play
### android beta
```
fastlane android beta
```
Ship to Playstore Alph testing.
### android playstore
```
fastlane android playstore
```
Release to app store.

----

## iOS
### ios SetupApp
```
fastlane ios SetupApp
```
Create App online 
### ios test
```
fastlane ios test
```
Runs all the tests
### ios certificates
```
fastlane ios certificates
```
Fetch and install the distribution certificates and provisioning profiles
### ios pushcerts
```
fastlane ios pushcerts
```
Create Push Notifications certs
### ios devices
```
fastlane ios devices
```
Registers developer devices with iTunes Connect
### ios beta
```
fastlane ios beta
```
Ship to Testflight.

Submit a new Beta Build to Apple TestFlight

This will also make sure the profile is up to date
### ios metadata
```
fastlane ios metadata
```
Upload application metadata to iTunes Connect
### ios screenshots
```
fastlane ios screenshots
```
Upload application screenshots to iTunes Connect
### ios release
```
fastlane ios release
```
Deploy a new version to the App Store

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
