# Sports X Next updates

## Latest published: 0.7.4-alpha

0.7.4 adds category-on-focus channel browsing, clearer programme blocks, main-sidebar focus transfer and automatic EPG interval controls. Highlight a category to change the channel list without pressing OK or tuning another stream. Right/OK enters the guide; Left from a channel label reopens categories.

Settings → Playback & guide now offers Manual, 6, 12, 24 or 48-hour EPG updates (default 12 hours). New sources load once in Manual mode. Failed downloads wait 30 minutes before automatic retry. Valid empty cached windows wait for the scheduled update; recent visible guide windows are cached. Manual Update EPG retains its selected-provider scope.

The main sidebar transfers focus into the selected page, including Playlists, Settings and reselecting the current page. Programme blocks follow real start/end times, label unavailable gaps and support adjacent-row and right-edge timeline navigation.

Release assembly, **86 unit tests** (zero failures/errors), full lint (zero errors, 56 warnings), APK identity/version and retained signing-certificate checks passed. Physical TV layout, remote focus, provider EPG and playback still need device testing. The all-channel background guide load remains; this is not a claim that every lag issue is resolved.

## Install or update

[Latest release](https://github.com/qamer6086-prog/sports-x-updates/releases/latest)

Next 0.5.0 or later: **Settings → Updates → Check for updates → Download → Install**. Earlier Next builds can install the APK manually. Android 7.0 or later. Same application ID and retained signing key preserve compatibility with Next 0.2 and later; the original 0.1 app has a separate identity.

Automatic app-update checks run daily after successful checks while the app is open. Use the manual check for a newly published release. Android confirms installation. No GitHub login/token is stored in the app; APK size/hash, application/version and installed signing certificate are checked.

## Source

The complete GPLv3 application source is the separately attached **public-source.zip** release asset with upstream notices. GitHub automatic source archives contain only this update-host repository.

Private signing keys and provider credentials are not published. No IPTV service or channels are included.
