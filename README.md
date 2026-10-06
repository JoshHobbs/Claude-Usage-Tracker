# Claude Usage Tracker (JoshHobbs fork) - Update Feed

This branch hosts the Sparkle `appcast.xml` and release zips for builds of this fork.

- **Appcast URL**: https://joshhobbs.github.io/Claude-Usage-Tracker/appcast.xml
- **Downloads**: `releases/Claude-Usage.zip`, signed with this fork's EdDSA key (`SUPublicEDKey` in the app's Info.plist)

Regenerate with Sparkle's `generate_appcast --account claude-usage-tracker-fork --download-url-prefix https://joshhobbs.github.io/Claude-Usage-Tracker/releases/ releases/`, then move `releases/appcast.xml` to the root.
