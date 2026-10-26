# Tamriel RP Launcher

[Download the latest Windows installer](https://github.com/SoCyan556/tamriel-rp-downloads/releases/latest)

Install the launcher, sign in with Discord, select your owned Steam copy of Skyrim Special Edition, and use Install & Update. You must be a member of the Tamriel RP Discord server (1564271071727980698). Membership is rechecked online before launch; non-members and unverified sessions cannot play through this launcher.

Discord sign-in opens in your normal browser using authorization-code + PKCE. Only identity and membership access are requested. No Discord password, client secret, bot token, email, or message access is included. Saved OAuth sessions use Windows user encryption.

Required SKSE and SkyMP files are downloaded from their upstream hosts, checked against signed release metadata, and installed with backups. Skyrim 1.6.1170 is required; the Steam depot workflow may ask you to scan a QR code in its own window.

Every launch checks the signed update feed. Required launcher and game-content updates must be installed before Play. Launcher membership/version checks do not yet prevent direct clients bypassing the launcher; enforcement on the game server requires the separate server admission integration.

This repository contains download releases and their signed manifest, not private signing keys, game files, or SKSE archives. The launcher is an unsigned Windows development build.

Update feed: `https://github.com/SoCyan556/tamriel-rp-downloads/releases/latest/download/stable.json`
