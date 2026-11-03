# BisBIM releases

The installers and the update feed of BisBIM, a desktop BIM app in development.

## Install

- macOS (Apple Silicon): download the `.dmg` from the latest release, open it, and drag BisBIM to Applications. The build is not notarized: for the first start, right click BisBIM and choose Open.
- Windows: download and run the `-setup.exe`. SmartScreen may ask once: choose More info, Run anyway.

## Updates

The app checks this repository at each start. When a newer release exists, it offers to update and restart. `File`, `Check for Updates…` checks at any time.

Each release holds the installers, the update artifacts with their signatures, and `latest.json`, which the app reads.
