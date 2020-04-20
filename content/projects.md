---
title: "Projects"
type: "page"
date: 2019-01-23T00:53:34Z
draft: false
---

### Android community distributions
I have contributed code to Android ROMs maintained by the community like CyanogenMod, it's successor [LineageOS](https://review.lineageos.org/q/owner:3skuero%2540gmail.com+status:merged) and [OmniROM](https://gerrit.omnirom.org/#/q/owner:%22Oliver+Garcia+Albertos%22+status:merged). Unfortunately after CyanogenMod disbanded most of the old commits were archived from their gerrit, so there's no easy way to retrieving all of them.

The most relevant ones, related to support for multimedia codecs from Novathor chipsets, are linked below:
- [native: Add missing changes for multimedia on STE devices](https://github.com/LineageOS/android_frameworks_native/commit/35c7cd72f91eedc77ab693ebb94121bdd57cc22c)
- [av: Missing changes for STE OMX multimedia](https://github.com/LineageOS/android_frameworks_av/commit/d8f7a185d0c541edcc229a21fce3661becdbab59)

All of this was done in the context of maintaining unofficial builds for my devices:

**Samsung Galaxy S3 Mini**
- [Device git repositories](https://github.com/Eskuero?tab=repositories&q=golden)
- [CyanogenMod 10](https://forum.xda-developers.com/showthread.php?t=2176244)
- [CyanogenMod 10.1](https://forum.xda-developers.com/showthread.php?t=2384232)
- [CyanogenMod 10.2](https://forum.xda-developers.com/showthread.php?t=2491332)

**Samsung Galaxy S4 Mini**
- [Device git repositories](https://github.com/Eskuero?tab=repositories&q=serranoltexx)
- [OmniROM 4.4](https://forum.xda-developers.com/galaxy-s4-mini/development/rom-omnirom-gt-i9195-t2807263)
- [TWRP Recovery](https://forum.xda-developers.com/showthread.php?t=2589011)

**Motorola Moto X Play**
- [Debloated device patches](https://github.com/Eskuero/patches_lineageos)
- [Barebones LineageOS 14.1](https://forum.xda-developers.com/moto-x-play/development/rom-barebones-lineageos-14-1-t3634188)

### Nino: Gradle automatizer
Nino is a python program to automatize the syncing, building, signing and deployment of your open source mobile applications using git, gradle and android system tools.

It allows granular configuration for each project, like which gradle tasks are assembled, which keystores are used for signing and what devices are deploy targets. You can get a feel of how it works and read the code by yourself on the [GitHub repository](https://github.com/eskuero/nino).

### Webextension: Collapsed Mastodon
[Mastodon](https://joinmastodon.org) is a distributed social network. A default user interface is provided as a web app, however certain things like the fixed drawer waste a lot of space.

This webextension collapses every useless container and integrates the reply boxes in the timelines in a TweetDeck style, all while keeping support for navigation through keybidings. It can be installed for Firefox from the [AMO](https://addons.mozilla.org/en-US/firefox/addon/collapsed-mastodon/) and for Chromium by following the instructions on the [GitHub repository](https://github.com/Eskuero/collapsed_mastodon#chrome).

### Other cool things
Although not as big and useful as the previously mentioned ones I've also done some other work.
- [Hexadecimal research of N3DS RAM](https://projectpokemon.org/home/forums/topic/37619-dump-online-battle-videos-from-codes/)
- [Mitigate doxxing on Twitter](https://gist.github.com/search?q=user%3Aeskuero+tweet)
- [Fzf wrapper as launcher](https://github.com/Eskuero/pyfzf-launcher)
- [Logic fixes on Savegame Editor](https://github.com/kwsch/PKHeX/commits?author=Eskuero)
- [Helper script for SSH tunnels as forwarders](https://github.com/Eskuero/tunnel_manager)
