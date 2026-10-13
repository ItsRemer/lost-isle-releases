# Lost Isle - client releases

**New players:** open [the latest release](https://github.com/ItsRemer/lost-isle-releases/releases/latest), download
`Lost.Isle-<version>.exe` and run it. It installs for your Windows user (no administrator prompt) with Java included,
and adds Lost Isle to the Start menu and desktop.

**Revision 241:** version 1.0.8 updates the client to RuneLite 1.13.1 for the matching Lost Isle server.
The existing custom content and HD NPC, scenery and player packs are retained. Your RuneLite profile stays in
the same location; this update does not reset your game account or progress.

**Updates install themselves.** Restart your existing Lost Isle launcher to receive 1.0.8.
Every time you start Lost Isle it checks this page; a new version downloads once
(a small "Updating Lost Isle..." window) and starts. You only need the setup again if the release notes say so.

What each release holds:

- `Lost.Isle-<version>.exe` - the Windows setup (only on releases that include a new one)
- `Isle.jar` - the client launcher the updater downloads (also runs on its own with Java 11 or newer: `java -jar Isle.jar`)
- `latest.json` - the signed description the updater reads; a download that does not match its signature is never run
- HD packs are referenced by their signed hashes and reused from earlier releases when unchanged.

This repository holds built releases only.
