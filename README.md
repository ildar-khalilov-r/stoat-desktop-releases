# stoat-desktop-releases

Built installers for a personal, self-hosted [Stoat](https://github.com/stoatchat) desktop client.

This repository holds **release artifacts only** — no source code is developed here. It exists
because the client connects to a private instance, and a private repository's Releases cannot be
downloaded anonymously, which the in-app updater and the instance's download page both need.

## What this is built from

The client is a modified build of [`stoatchat/for-desktop`](https://github.com/stoatchat/for-desktop).
The modifications are small: the build is pointed at a private instance, and the updater and
publisher are pointed at this repository.

## Source

`stoatchat/for-desktop` is licensed under the **GNU Affero General Public License v3.0**, and so is
every binary published here.

If you received a build from this repository, you are entitled to the complete corresponding source
code for that build. Open an issue on this repository naming the release you have, and the source
for it will be provided.

Upstream source, which these builds are derived from, is public at
<https://github.com/stoatchat/for-desktop>.

## No warranty

These are personal builds published for a small group. They are provided as-is, with no warranty,
to the extent permitted by the licence.
