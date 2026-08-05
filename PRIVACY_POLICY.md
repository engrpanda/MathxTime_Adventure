# MathxTime Adventure Privacy Policy

_Last updated: August 5, 2026_

**Developer:** EngrPanda
**Contact:** support.engrpanda@gmail.com

This policy explains what information MathxTime Adventure ("the app") collects, how it's used,
and the choices you and your child have — written for both parents and Google Play review.

## Summary

- No account, email address, or real name is ever required to play.
- Almost everything (profile, progress, coins, gems, streaks) stays on the device.
- The only feature that sends anything off the device is **Competitive Mode**, which is **off by
  default** and requires a parent/guardian to pass a simple math gate before it can be turned on.
- The app shows no advertising. It offers optional real-money in-app purchases (Crystal Packs),
  gated behind a parental math challenge before the purchase sheet opens.

## Information stored locally on your device

When a player sets up a profile, the app stores the following **on-device only** (via local
storage, not uploaded anywhere):

- A player-chosen nickname (not a legal name) and, optionally, a school name
- A selected companion/avatar
- Progress: level, XP, coins, gems, login streaks, unlocked titles/themes/achievements

This data stays on the device and is never transmitted unless Competitive Mode is turned on (see
below). It persists until the app is uninstalled or the player resets their profile from Settings.

## Competitive Mode (off by default)

Competitive Mode is the **only** feature that sends any player-entered information off the
device. It is disabled by default, and turning it on requires answering a simple multiplication
problem — a parental gate intended to keep young children from enabling it without a parent or
guardian present.

When Competitive Mode is on, after each game the app uploads the following to a public,
world-readable leaderboard (Google Firebase Firestore):

- Nickname and chosen avatar
- School name, only if the player entered one
- Game mode, score, accuracy, and completion time
- A randomly generated, anonymous device ID (not linked to any personal account)

**Never collected or uploaded, at any time:** real name, email address, phone number, physical
address, city/province/country, precise location, age, or grade level.

Because the leaderboard is public, the app runs entered nicknames and school names through an
on-device filter that blocks profanity and personal-information patterns before anything is sent.
This is a lightweight safeguard, not a guarantee — players and parents should still choose
nicknames that don't reveal personal information.

To remove your own leaderboard entries, use **Settings → Delete Leaderboard Data** in the app —
no email required. If you need an entry removed from a device you no longer have (so the in-app
option isn't available to you), email **support.engrpanda@gmail.com** with the nickname and
approximate date of the score.

## Handwriting recognition

The app's handwriting practice feature uses Google's ML Kit Digital Ink Recognition. After a
one-time model download, handwriting strokes are recognized **entirely on the device** — stroke
data is never uploaded to a server.

## Sign-in

The app uses Firebase Authentication in **anonymous mode** to give each device a private,
random ID. No email, password, phone number, or third-party account is ever requested.

If a player links a Google Play Games account (used only to support Competitive Mode features
like sign-in), that is handled directly by Google Play Games Services under Google's own privacy
policy.

## Diagnostics and analytics

The app uses:

- **Firebase Crashlytics** to receive crash reports so we can fix bugs. Crash reports are not
  linked to a player's identity.
- **Firebase Analytics** to understand aggregated usage patterns (e.g. which game modes are
  played). This data is not linked to individual player identities and is not used for
  advertising.

## Advertising

The app shows **no advertisements** and does not use any ad network or ad SDK.

## Purchases

The app includes an in-game virtual currency (Coins and Crystals/Gems) earned by playing, used to
unlock cosmetic pens and companions. Crystals can also be bought with real money in fixed-price,
fixed-quantity "Crystal Pack" bundles (for example, a specific price for a specific number of
Crystals — never a randomized reward, loot box, or mystery prize).

Real-money purchases are processed entirely by Google Play Billing — this app never sees or
stores payment card details, billing address, or other payment information. Before the Play
purchase sheet opens, the app shows the same parental math challenge described above under
Competitive Mode, so a young child can't complete a real-money purchase without a parent or
guardian present.

## Server-side voucher redemption

If a player redeems a promotional voucher code, the code and the player's anonymous device ID are
sent to a server function to validate and apply the reward. No other personal information is
involved.

## Third-party services we use

The app relies on the following Google services. Each processes data under Google's own privacy
terms, linked below:

- **Google Play Games Services** (optional sign-in) — https://policies.google.com/privacy
- **Firebase Authentication** (anonymous mode) — https://firebase.google.com/support/privacy
- **Firebase Analytics** — https://firebase.google.com/support/privacy
- **Firebase Crashlytics** — https://firebase.google.com/support/privacy
- **Cloud Firestore** (leaderboard storage) — https://firebase.google.com/support/privacy
- **Google Play Billing** (in-app purchases) — https://policies.google.com/privacy
- **ML Kit Digital Ink Recognition** (on-device handwriting recognition) —
  https://developers.google.com/ml-kit/terms

### International data transfers

Because Firebase and other Google services may process and store data on servers located outside
your country, any information sent through Competitive Mode (see above) may be transferred to and
processed on Google's servers in accordance with Google's Privacy Policy
(https://policies.google.com/privacy). Handwriting recognition via ML Kit happens entirely on your
device and is not transferred anywhere.

## Children's privacy

MathxTime Adventure is designed to be safe for children to use without adult supervision for its
core, offline experience. No account, real name, or email is ever required. The only feature that
sends any information off the device — Competitive Mode — is off by default and gated behind a
parental math challenge. We do not knowingly collect real names, contact information, or precise
location from any user, child or adult. We do not use data collected from children for advertising
or profiling.

## Data retention and deletion

- On-device data (profile, progress) is deleted when the app is uninstalled, or immediately if the
  player uses the in-app profile reset.
- Leaderboard entries can be deleted at any time from **Settings → Delete Leaderboard Data**,
  which removes every entry that device has ever submitted, across every world and mode,
  immediately. You can also request removal by emailing support (see Contact below) if you'd
  rather not use the in-app option, or if the entry was submitted from a device you no longer
  have access to.

## Changes to this policy

If this policy changes, we'll update this document and the "Last updated" date above.

## Contact

Questions or requests about this policy or your data: **support.engrpanda@gmail.com**
