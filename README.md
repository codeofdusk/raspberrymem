# Raspberrymem
Raspberrymem is a free memory aid for the [Raspberry Pi](http://raspberrypi.org). It was created as a working prototype of a project for the 2012 [First Lego League](http://firstlegoleague.org) Senior Solutions challenge.

I wrote this at about age 12 or 13. Before then, I had done some programming but was unfamiliar with version control and standard open-source "development practices." This was my first "open-source project."

This Github import contains the last sixty or so commits. The very first part of the history was stored on Google Code and has been lost. The project had a website and pre-made images for the original Raspberry Pi, which have also been lost. This project almost definitely has bugs, and is entirely unsupported.

## Starting Raspberrymem
To start Raspberrymem, run `./ui` from the `raspberrymem` directory.

## "Post-EOL" Patches
Networking has been disabled in this version, as the server it relied on no longer exists and the original server source was lost. If you wish to re-enable it, see the last few commits and/or relevant source code comments.

Raspberrymem may report its version or device ID as "EOL" (end-of-life). It will attempt to update from Git instead of the original Bazaar repo on Launchpad.
