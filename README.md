[update-readmes]   Mode: rewrite — migrating to template structure...
# btrfs-home-directory-snapshots

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/btrfs-home-directory-snapshots)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/btrfs-home-directory-snapshots.git
cd btrfs-home-directory-snapshots
```

## Usage


The first step is to convert one or more home directories into btrfs subvolumes. The `home2subvolume` script is called with one or more usernames and it performs this conversion.
The `home2subvolume` script must be run as root and only when the home directory
to be converted is not in use. A backup of the home directory is a good idea.

This is an example. We add two test users, `test` and `etest`. User `test` has a regular home directory and `etest`'s home directory is encrypted with ecryptfs.

```
$ sudo -i
# cd /
# adduser test
 ...

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/btrfs-home-directory-snapshots`](https://github.com/Interested-Deving-1896/btrfs-home-directory-snapshots) and mirrored through:

```
Interested-Deving-1896/btrfs-home-directory-snapshots  ──►  OpenOS-Project-OSP/btrfs-home-directory-snapshots  ──►  OpenOS-Project-Ecosystem-OOC/btrfs-home-directory-snapshots
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/btrfs-home-directory-snapshots/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
