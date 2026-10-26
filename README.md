# Sports X Next updates

Public Android TV releases and in-app update metadata for Sports X Next.

## Latest: 0.7.0-alpha

Live TV now supports per-provider/profile UK or multi-country category filters, unlabelled-category controls, manual Show/Hide exceptions and a preview. Categories support provider, alphabetical and manual ordering; channels support provider, alphabetical, number, saved manual order and favourites first. Up/Down follows the filtered provider list.

UK setup: Channels > choose provider > Smart categories & sorting > UK only > review preview > Apply filters & order. No channels are deleted.

The player adds now/next information, Hold OK quick actions and a TV guide timeline. The guide reads visible channels in two-hour windows while playback continues. Full release notes and the APK are on the latest release page.

### Existing features

This release adds a navy-and-lime TV design with an expanding sidebar, sports-art Home hub, personal live/next picks and consistent event cards. Event pages bring together recommended feeds, evidence/provider labels, alternatives, available recordings and catch-up.

Save individual events or follow entire sports alongside teams and competitions. The local QR phone session can search fixtures and send Open/Watch requests to the TV. Playback requests recheck current live availability and visibility/parental settings. Opening the event or playback closes that temporary pairing session.

Refreshes keep existing fixtures visible. Channel rows reserve selection detail space, feed ranking runs off the UI thread, and empty Live TV does not initialise a player. Diagnostics includes section-level Sports frame percentiles for device testing.

## Install or update

[Open the latest release](https://github.com/qamer6086-prog/sports-x-updates/releases/latest) and download its `.apk` asset. Android 7.0 or later is required.

Existing Sports X Next 0.5.0 or later: **Settings → Updates → Check for updates → Download → Install**. Earlier Next builds can install the latest APK manually. The same application ID and retained signing key preserve compatibility with Next 0.2 and later. The original 0.1 app has a separate identity.

The repository `qamer6086-prog/sports-x-updates` is preconfigured. You choose when to download and Android confirms installation. Allow Sports X as an installation source if requested, and install after active recordings finish. Checks run at most daily after a successful check while the app is open; use the manual check for a newly published release.

## Source and verification

The complete application source is the separately attached **`…-public-source.zip`** release asset, licensed under GPLv3 with upstream notices included. GitHub's automatically generated source archives contain this update-host repository, not the application source.

0.7.0 passed 71 unit tests, release assembly, full lint with no errors and APK signing verification. Physical TV visuals, remote focus, playback, phone pairing and scrolling performance still need testing. No on-device performance improvement is claimed.

Feed evidence describes matching and past playback, not verified programme content. Coverage, catch-up and recording depend on the available data and the user's provider/device.

Private signing keys and provider credentials are not published. No IPTV service or channels are included. The TV updater uses HTTPS, exact size/SHA-256, application/version checks and matching installed signing certificates; no GitHub login or token is stored in the app.
