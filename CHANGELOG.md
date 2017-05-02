## 0.5.0 Release notes (02-05-2017)

### Braking changes

- `sharedObject` is now a property and available as `shared` property in Swift.

### Behaviour changes

- `checkForUpdates` now checks for update even if another check wasn't finished.
- Changing `localizationType` doesn't call `checkForUpdates` automatically anymore. **Call `checkForUpdates ` manually after changing `localizationType` property**

### Fixes

- Updated `localizationType` documentation. 

## 0.4.1 Release notes (21-04-2017)

### Fixes

- Default `localizationType` fix.

## 0.4.0 Release notes (18-04-2017)

### New

- Added `localizationType` property for linear control of localization source.
- Added `setAPIToken:projectID` method for easy lokalise setup flow.

### Braking changes

- Removed `preReleaseLocalization` in favour of `localizationType`.
- Removed `forceLocalLocalization` in favour of `localizationType`.
- Renamed `token` to `apiToken`.

### Other

- Info.plist setup flow is still supported but is depreciated.
- All `LokaliseDelegate` methods are optional now.