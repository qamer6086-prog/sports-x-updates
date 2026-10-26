# Sports X Next updates

Public Android TV releases and in-app update metadata for Sports X Next.

## Latest published: 0.7.3-alpha

0.7.3 makes the compact TV guide the main Channels screen, with aligned channel names/logos, timed programme blocks, time headings and a current-time marker. Live preview and focused programme details sit above the guide. Categories fold away for more timeline space, and the source selector uses a single-line control. Select a different channel to preview it; select the playing channel again for fullscreen.

Provider-only EPG refresh and stream resolution/FPS information remain included. Native TV layout, D-pad focus, provider guide matching and playback still need device checking. No broader playback-lag or provider-data repair is claimed.

### Included from 0.7.2

0.7.2 gives the Live TV category sidebar consistent row heights, clearer gaps, larger labels and trailing channel counts. Its source selector now opens a dropdown above the categories on the left. Opening Updates transfers remote focus to its main action so the navigation sidebar can collapse, including Settings → Updates.

Physical TV spacing, provider dropdown navigation and sidebar focus still require device checking.

### Included from 0.7.1

0.7.1 makes the Channels Update EPG button refresh only the selected provider. All providers asks you to choose one. Other providers’ cached listings are retained; a shared XMLTV file still requires its complete download. Normal automatic/global updates keep their existing scope.

The fullscreen player panel and channel preview now show source-video quality (UHD/FHD/HD/SD), exact resolution and declared frame rate, including fractional rates. Missing frame rate is shown as unavailable. Values follow the decoded track rather than the channel name or TV output mode.

**The broader Live TV/EPG lag fixes remain pending.** This release does not remove the all-channel background guide load or all overlapping requests and screen updates.

### Included from 0.7.0

0.7.0 adds per-provider/profile UK or multi-country category filters with preview and manual overrides, category/channel sorting and filtered channel switching. The player includes a now/next panel, Hold OK quick actions and a TV guide timeline. Updates now has clearer status/version cards, last successful check time, download progress and foldaway Advanced settings.

**UK setup:** Channels → choose provider → Smart categories & sorting → UK only → review preview → Apply filters & order. Matching uses category labels and supported country flags; no channels are deleted.

The guide reads visible channel rows and two-hour windows while playback continues. Existing event dates, manual EPG refresh and the clean channel browser remain included.

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

The 0.7.3 APK version (code 14), application identity, size/SHA-256 and retained signing certificate were independently checked at publication. The bundled 79 unit-test reports have zero failures/errors. Historical build/lint reports are labelled in the source verification notes; no fresh build/lint run was performed during publication. Physical TV visuals, remote focus, playback, phone pairing and scrolling performance still need testing. No on-device performance improvement is claimed.

Feed evidence describes matching and past playback, not verified programme content. Coverage, catch-up and recording depend on the available data and the user's provider/device.

Private signing keys and provider credentials are not published. No IPTV service or channels are included. The TV updater uses HTTPS, exact size/SHA-256, application/version checks and matching installed signing certificates; no GitHub login or token is stored in the app.
