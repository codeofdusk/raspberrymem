# Raspberrymem
Raspberrymem is a free memory aid for the [Raspberry Pi](http://raspberrypi.org). It was created as a working prototype of a project for the 2012 [First Lego League](http://firstlegoleague.org) Senior Solutions challenge. It can store reminders, timers and notes, run a graphical desktop modified for ease of use, and be remotely manipulated through a server. The interface is completely keyboard driven, easy to navigate and available in both English and Mexican Spanish.

Raspberrymem is designed to be run from a text console on a Debian-based Linux distribution, like Debian, Raspbian or Ubuntu. This client was written in bash script. The original server was written in [MOO](https://en.wikipedia.org/wiki/MOO), and I started [a rewrite to Python](http://github.com/codeofdusk/raspberrymem-server).

I wrote this at about age 12 or 13. Before then, I had done some programming but was unfamiliar with version control and standard open-source "development practices." This was my first "open-source project."

This Github import contains the last sixty or so commits. The very first part of the history, which I've lost, was stored on Google Code. The project had a website and pre-made images for the original Raspberry Pi, which have also been lost. This project almost definitely has bugs, and is entirely unsupported.

## Starting Raspberrymem
To start Raspberrymem, run `./ui` from the root of this repo.

## "Post-EOL" Patches
Networking has been disabled in this version, as the server it relied on no longer exists and the original server source was lost. If you wish to re-enable it, see the last few commits and/or relevant source code comments.

Raspberrymem may report its version or device ID as "EOL" (end-of-life). It will attempt to update from Git instead of the original Bazaar repo on Launchpad.
