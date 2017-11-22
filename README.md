# ionic-fastlane

## Command line snippets to execute fastlane lanes in bulk

### iOS

```
FASTLANE_DISABLE_COLORS=1; for l in build_debug_debug_ionic build_debug_ionic build_release_ionic build_debug_cordova build_release_cordova build_debug_native build_release_native; do fastlane ios $l | tee "artifacts/ios $l.log"; done
```

### Android

```
FASTLANE_DISABLE_COLORS=1; for l in build_debug_debug_ionic build_debug_ionic build_release_ionic build_debug_cordova build_release_cordova build_debug_native build_release_native; do fastlane android $l | tee "artifacts/android $l.log"; done
```
