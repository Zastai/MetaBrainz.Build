# MetaBrainz.Build

This used to be a collection of build support files, pulled in (as a git
submodule) by other `MetaBrainz.xxx` projects.

However, it has since been upgraded to be a separate project that produces
an MSBuild SDK package, setting up the same thing, but without needing
submodules.

## Contents

### Initial Project Contents

These are files that should be copied to the top of new `MetaBrainz.xxx`
projects.

### The SDK

This consists of:

- MSBuild props/targets files
- a default package icon (using the basic MetaBrainz logo)
- the strong naming key to be used

At some point, this could be extended to include MSBuild tasks, should they
become useful; in the meantime, there is no code present.

## Release Notes

### v1.0.2 (not yet released)

### v1.0.1 (2021-08-05)

- Switched the package license to MIT.
- Added the MIT license file.

### v1.0.1 (2020-12-21)

Initial release.
