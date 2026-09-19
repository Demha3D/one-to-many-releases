# One to Many for macOS

Turn a source recording or text into a reviewed content library.

[Download the latest release](https://github.com/Demha3D/one-to-many-releases/releases/latest)

Requires **macOS 14 or later** and **Apple Silicon (M1 or newer)**. For a first installation, download the ARM64 DMG, open it, and drag One to Many into Applications.

## Online updates

Choose **Check for Updates** to read release notes. Version 0.2.5 uses a nonmodal Updates window so it does not block the app from quitting during installation.

- **Running 0.2.4 or earlier:** save your edits, quit the app, open the latest signed DMG and replace One to Many in Applications once. Older in-app installers can get stuck waiting for their Updates dialog to close. If the old app will not quit after cancelling installation, close it through macOS Force Quit before replacing it. Saved projects remain in the library on your Mac.
- **Running 0.2.5 or later:** choose **Download update**, then **Restart & update** when ready, or **Later** to keep the verified download. Save editor changes and let active generation and exports finish first. The updater replaces the app and relaunches it. Launch the app from a writable Applications location, not from a mounted DMG.

Automatic update checks run at launch and every six hours from version 0.2.1. A new version is announced once; downloading and installation remain your choice.

Downloads are checked against GitHub's SHA-256 digest, the publisher's Developer ID signature and Apple notarization. The in-app installer also requires a matching Ed25519-signed Sparkle feed. Each release includes SHA256SUMS.txt; releases starting at 0.2.2 also include appcast.xml.

A local preview can use a separate test library. Those test edits are not automatically merged into the installed app's library.

## Repository contents

Release information and binary installers only. Application source code and user content are not published here. Platform channel choices create local drafts; they do not connect or publish to social accounts. Online AI and cloud features require their respective configuration and access.
