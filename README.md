# Board releases

Signed builds of **Board**, a personal work board for macOS, and the [Sparkle](https://sparkle-project.org) feed it checks for updates.

- **Download:** the newest DMG is under [Releases](../../releases/latest). Board needs macOS 26.
- **Updates:** installed copies read `appcast.xml` once a day (or on **Board ▸ Check for Updates…**) and update themselves.
- **Trust:** every DMG is notarized by Apple and signed with Board's Ed25519 update key, and so is `appcast.xml`. Board refuses an update or a feed the key doesn't verify.

`items/` holds one appcast entry per release; `appcast.xml` is rebuilt from the newest ten and signed on every release.
