# HEVLI Releases

Official HEVLI Workspace downloads will be published here after each installer
has passed its platform signing, clean-computer installation, account and update
checks.

## Current availability

There are no public installers yet. The HEVLI website's early-access form stays
available until the Mac beta is signed, notarized and verified on a separate
Mac. Windows downloads will appear only after Authenticode signing and separate
Windows verification.

## Release contents

Each verified release is expected to include the platform installer, signed
updater payload and `latest.json` manifest, `SHA256SUMS`, build information, a
source archive for the exact release commit, and license and third-party
notices. Source archives contain a source snapshot and omit Git history and
unreleased branches.

The desktop source archive retains the applicable MPL-2.0 terms and notices.
The separate HEVLI backend is AGPL-3.0-only; its matching source must also be
made available to people interacting with the hosted service. Each release
will identify the matching backend source snapshot once its deployed commit has
been confirmed.

## Download safety

Use only the installer linked from a published release here. Check the
`SHA256SUMS` file and platform signature before installing. HEVLI Workspace
updates are accepted only when they verify against the updater public key built
into the installed application.
