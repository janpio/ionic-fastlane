fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></th>
<th width="33%">Installer Script</th>
<th width="33%">RubyGems</th>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Available Actions
## iOS
### ios build_debug_debug_ionic
```
fastlane ios build_debug_debug_ionic
```
Build Debug Debug Ionic
### ios build_debug_ionic
```
fastlane ios build_debug_ionic
```
Build Debug Ionic
### ios build_debug_cordova
```
fastlane ios build_debug_cordova
```
Build Debug Cordova
### ios build_debug_native
```
fastlane ios build_debug_native
```
Build Debug Native
### ios beta
```
fastlane ios beta
```
Submit a new Beta Build to Apple TestFlight

This will also make sure the profile is up to date
### ios release
```
fastlane ios release
```
Deploy a new version to the App Store

----

## Android
### android build_debug_debug_ionic
```
fastlane android build_debug_debug_ionic
```
Build Debug Debug Ionic
### android build_debug_ionic
```
fastlane android build_debug_ionic
```
Build Debug Ionic
### android build_debug_cordova
```
fastlane android build_debug_cordova
```
Build Debug Cordova
### android build_debug_native
```
fastlane android build_debug_native
```
Build Debug Native
### android beta
```
fastlane android beta
```
Submit a new Beta Build to Crashlytics Beta
### android build_release_ionic
```
fastlane android build_release_ionic
```
Build Release Ionic
### android build_release_cordova
```
fastlane android build_release_cordova
```
Build Release Cordova
### android build_release_native
```
fastlane android build_release_native
```
Build Release Native
### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
