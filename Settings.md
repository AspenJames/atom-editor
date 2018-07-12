# Settings

* These settings override default and can be found at `~/.atom/config.cson`
* Copy the contents below to your  `config.cson` file, or pick and choose as appropriate.
* I've left the `userId` here blank, since it is unique to each user. `exception-reporting` is a core package on Atom, and should be enabled by default once `telemetryConsent` is turned on.

## config.cson
```
"*":
  core:
    restorePreviousWindowsOnStart: "no"
    telemetryConsent: "limited"
    themes: [
      "atom-dark-ui"
      "solarized-light-syntax"
    ]
  editor:
    fontSize: 12
    scrollPastEnd: true
    showIndentGuide: true
    softWrap: true
    softWrapAtPreferredLineLength: true
    softWrapHangingIndent: 1
  "exception-reporting":
    userId:
  "file-icons":
    onChanges: true
  pigments:
    markerType: "native-dot"
  "tree-view": {}
  welcome:
    showOnStartup: false
```
