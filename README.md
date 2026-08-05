# mirabot-cef-releases

Public release artifacts for [`mirabot-cef`](https://github.com/joedwy/mirabot-cef)
(private repo) — the Sparkle appcast (`appcast.xml`) and, via GitHub
Releases, the signed/notarized `.dmg` for each version.

No source code lives here. This repo exists only because Sparkle's update
checker and GitHub's release-asset URLs need to be publicly reachable
without authentication, and `mirabot-cef` itself is private.

This repo is managed entirely by `mirabot-cef`'s `scripts/release.sh` — the
version history in `appcast.xml` and the Releases tab are generated, not
hand-edited.
