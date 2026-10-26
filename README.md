# Tamriel RP Launcher

[Download the latest Windows installer](https://github.com/SoCyan556/tamriel-rp-downloads/releases/latest)

Install the launcher, select your owned Steam copy of Skyrim Special Edition, and use Install & Update. Required SKSE and SkyMP files are downloaded from their upstream hosts, checked against signed release metadata, and installed with backups. Skyrim 1.6.1170 is required; the Steam depot workflow may ask you to scan a QR code in its own window.

Every launch checks the signed update feed. Required launcher and game-content updates must be installed before Play. This does not yet prevent clients bypassing the launcher; enforcement on the game server requires a separate server integration.

This repository contains download releases and their signed manifest, not private signing keys, game files, or SKSE archives. The launcher is an unsigned Windows development build.

Update feed: `https://github.com/SoCyan556/tamriel-rp-downloads/releases/latest/download/stable.json`
