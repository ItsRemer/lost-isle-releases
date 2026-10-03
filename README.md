# Lost Isle - client releases

**New players:** open [the latest release](https://github.com/ItsRemer/lost-isle-releases/releases/latest), download
`Lost.Isle-<version>.exe` and run it. It installs for your Windows user (no administrator prompt) with Java included,
and adds Lost Isle to the Start menu and desktop.

**Updates install themselves.** Every time you start Lost Isle it checks this page; a new version downloads once
(a small "Updating Lost Isle..." window) and starts. You only need the setup again if the release notes say so.

What each release holds:

- `Lost.Isle-<version>.exe` - the Windows setup (only on releases that include a new one)
- `Isle.jar` - the client launcher the updater downloads (also runs on its own with Java 11 or newer: `java -jar Isle.jar`)
- `latest.json` - the signed description the updater reads; a download that does not match its signature is never run

This repository holds built releases only.