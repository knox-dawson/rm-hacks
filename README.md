# rM Hacks

This repository is meant to share small improvements and tweaks for rM devices,
covering both revisions (1 and 2).
These changes don't alter the application's core code directly
but impact how it functions.
Before using them, please read the disclaimer below.

## Disclaimer

This repository contains patches and modifications for third-party software,
which are provided "as-is" and without warranty of any kind, express, implied,
or otherwise, including but not limited to the warranties of merchantability,
fitness for a particular purpose, and non-infringement.

The patches provided here are intended to enhance or modify the functionality of
the respective third-party software, and their use is at your own risk.

Please note that the original software is subject to its own licensing terms
and conditions, and this disclaimer only covers the patches and modifications
provided within this repository. Ensure that you comply with the original
software's licensing requirements when using these patches.

## Installation

For your convenience, we've provided an automated installation script for installation.

1. Connect to your rM device via SSH.
2. Paste the below command, then press Enter.
3. Follow the on-screen instructions.

```shell
(installation command will be provided soon, stay tuned!)
```

## Patches

### Version 0.0.1

Our first patch, a pilot and proof of concept, is designed to bring back some
popular features for devices updated to version 3.6.1.1894.

If you're still using a device with version 2.x, you might prefer using
[ddvk's Binary Patches](https://github.com/ddvk/remarkable-hacks).

This patch includes the following changes:

- The Lamy Pen button now works for erasing (only erasing for now).
  To use this feature, install
  [ddvk's Qt Plugin for Lamy Pen](https://github.com/ddvk/remarkable-stylus) first.
- The toolbar icon changes from the default open icon to a brush icon.
- The close icon (x) in the top right corner has been removed.
