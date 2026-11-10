# BYD Cockpit Releases

This public repository distributes BYD Cockpit release APKs. Application source code and source history remain in a separate private repository and must not be pushed here.

## Release channels

- Main/stable releases use normal version tags (for example, `v0.1.0`) and are published with GitHub's prerelease flag off.
- Development releases use SemVer prerelease versions (for example, `v0.1.0-dev.3`) and are published with the prerelease flag on.
- Stable-channel update checks should ignore prereleases. Development-channel checks may consider all releases.

Release assets are the supported distribution artifacts. The source archives GitHub generates for this repository contain only its release documentation, not the application source.

Debug-signed APKs are for testing only. Vehicle installation or changing the default launcher requires separate approval and acceptance testing.