# osu-ios-kit

Build an unsigned iOS IPA of osu!lazer (from upstream source) using GitHub Actions, then sideload/sign on Windows.

This repo contains:
- GitHub Actions workflow to build an unsigned IPA on macOS runners
- Patch files to add custom server support (to be added)
- Documentation for Windows sideloading

----------------------
Please note, this is an active work in progress, this would be private but I don't really feel like messing with PAT for this as it's not really a concern for being public just know this is not functional (WELL it is, it'll build a functional ipa, just not private server shit rn) 