# Arjika privacy policy

Effective 1 November 2026.

Arjika backs up the photos and videos on your phone to **your own Mac**, and lets you browse them there. It is made
for one household and works only with a Mac you own and run.

## Where your photos go

- Photos, videos and their details are sent only to the Arjika server on **your own Mac**. They travel over your
  own private network (a Tailscale or Headscale "tailnet"), encrypted with TLS 1.3. Your phone accepts only your
  Mac's key, which you pinned when you paired.
- On the Mac they are stored encrypted, on a drive you choose.
- The developer runs **no server**. Your photos never pass through the developer or anyone else, and the developer
  cannot see them.

## What the app collects

Nothing for the developer. Arjika has:

- no account and no sign-in;
- no analytics, telemetry, advertising or crash reporting;
- no third-party services.

No data is sold, shared or transferred to anyone.

## What the app uses on your phone, and why

| Permission | Why |
| --- | --- |
| Photos and videos (all, or the ones you select) | To back them up to your Mac. You choose all or selected photos in Android's dialog. |
| Photo location (`ACCESS_MEDIA_LOCATION`) | To keep a photo's location with the backup, so your Mac can show where it was taken. Place names are worked out on your Mac, offline. |
| Notifications | To show backup progress. Backups still run if you decline. |
| Network and background work | To upload to your Mac while the app is closed, under your Wi-Fi-only and charging settings. |
| Screen lock / fingerprint check | To confirm it is you before you add or remove a device. Arjika never sees your PIN or fingerprint. |

## What stays on your phone

Arjika keeps on your phone:

- a device key, held in Android's secure key store, which it cannot export;
- your Mac's address and pinned key;
- a list of photos waiting to upload.

None of this leaves your phone except to talk to your own Mac. It is excluded from Android cloud backups.

## Deleting your data

- **On the phone:** uninstall Arjika, or clear its storage in Android settings. That removes everything it kept on
  the phone.
- **On the Mac:** your photos stay on the drive you control. You can revoke the phone from the Mac or another paired
  device, and delete files there as you wish.

## Children

Arjika is not directed at children.

## Changes

If this policy changes, the new version is published at this address with a new effective date.

## Contact

Use the developer contact address shown on Arjika's Google Play listing.
