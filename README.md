# Sports X Next updates

Public Android TV releases and in-app update metadata for Sports X Next.

## Install

[Open the latest release](https://github.com/qamer6086-prog/sports-x-updates/releases/latest) and download the `Sports-X-Next-…apk` asset. Install 0.5.0 manually once to enable the in-app updater. Android 7.0 or later is required.

This updates Sports X Next 0.2–0.4.2 in place using the retained signing identity. The original 0.1 app has a separate application ID.

## In-app updates

Open **Settings → Updates → Check for updates**. The repository `qamer6086-prog/sports-x-updates` is preconfigured. You choose when to download, and Android asks you to confirm installation. Allow Sports X as an installation source if Android requests it. Install after active recordings finish.

Successful update checks run at most daily after opening the app. Future published releases need a higher version code and the same signing identity. With version 0.5.0 installed and hosted, the check should report up to date.

Downloads require HTTPS, matching size and SHA-256, correct application ID and version, and matching installed signing certificates. No GitHub token or login is needed in the TV app.

## Source

The complete application source is the separately attached **`…-public-source.zip`** release asset, licensed under GPLv3 with upstream notices included. GitHub's automatically generated “Source code” archives contain this update-host repository, not the application source.

Private signing keys and provider credentials are not published. No IPTV service or channels are included.

## Verification

0.5.0 passed 50 unit tests, release assembly, full lint with no errors, and APK signing checks. On 26 October 2026 the public latest `update.json` URL returned HTTP 200 and its APK downloaded with the exact declared size and SHA-256. The installation and permission screens still need testing on a physical Android TV.
