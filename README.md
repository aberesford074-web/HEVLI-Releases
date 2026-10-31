# HEVLI Releases

Official HEVLI Workspace downloads will be published here after each installer
has passed platform-specific installation, launch, account and update checks.

## Current availability

The [1.0.4-beta.1 source-only prerelease](https://github.com/aberesford074-web/HEVLI-Releases/releases/tag/sources-v1.0.4-beta.1)
contains desktop and hosted-backend source snapshots, licence files, notices
and checksums. It contains no application installers.

There are no public installers yet. The unsigned macOS Apple Silicon beta is
being verified in an isolated environment; Gatekeeper warnings are expected.
The Windows x64 installer still needs a clean install and launch test. The
HEVLI website's early-access form stays available until installers are verified
and approved for release.

## Release contents

Each verified application release is expected to include platform installers,
the signed updater payload and `latest.json` manifest, `SHA256SUMS`, build
information, a source archive for the exact release commit, and licence and
third-party notices. Source archives contain a source snapshot and omit Git
history and unreleased branches.

The desktop source archive retains the applicable MPL-2.0 terms and notices,
omits Git history, and excludes one updater test-only private RSA fixture with a
separate explanation file. The desktop snapshot corresponds to commit
`fe586745fa51091165eec10074174d17f4ec87c1`.

The separate HEVLI backend is AGPL-3.0-only. The source-only prerelease includes
the backend snapshot matching the live Render commit
`25fa1a872ab409388050a24e6b2a147552824cf3`.

## Download safety

Use only the installer linked from a published release here. Check the
`SHA256SUMS` file and platform signature before installing. HEVLI Workspace
updates are accepted only when they verify against the updater public key built
into the installed application.
