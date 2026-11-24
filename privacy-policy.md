# Mystica Privacy Policy

Effective date: 2026-11-24

Contact: albert_lqchen@hotmail.com

Mystica is an iPhone app for reflection and entertainment. This policy says, in plain words, what the app
keeps on your phone, what (if anything) leaves it, and who receives it. It describes version 1.0.

The short version: **we run no servers for this app and we receive none of your data.** The app has no
accounts, no ads, no analytics and no tracking, and we never sell data. By default everything stays on your
phone. Data leaves your phone only in the three cases listed under "What is sent, where, and when".

## Who we are

Mystica is published by Liqun Chen. You can reach us at albert_lqchen@hotmail.com.

## What stays on your phone

- **Birth profile** (name, birth date and time, birthplace), if you enter one for the methods that use it. It
  is stored in the iOS Keychain, not in plain files.
- **API keys**, if you add your own cloud key. They are stored in the iOS Keychain, accessible only on this
  device after it has been unlocked once, and are never written to logs or to ordinary preferences.
- **Journal**: your saved readings (your question, the drawn signs, the narration, follow-up chat and Lantern
  hints). It is one file in the app's private storage, with iOS file protection, excluded from device backups.
- **Preferences** such as language, haptics and the Lantern setting.
- **Voice**: audio is used only while you are dictating, is turned into text on your phone, and is not saved.
  Only the resulting text is kept, as if you had typed it.
- **Palm photo**: held in memory for the reading, resized, and not saved by the app (the app has no copy
  after the reading screen is left, unless your own Photos library or camera roll keeps it).

By default the narration is produced by Apple's on-device model, so your question and the drawn signs are
processed on the phone and nothing is transmitted.

## What is sent, where, and when

1. **Optional cloud narration (off by default).** Only if you choose Claude (Anthropic) or OpenAI in the app,
   switch on "Send readings to the cloud", and enter your own API key, the app sends a request directly from
   your phone to that company's servers over HTTPS. The request contains: your question; the drawn signs and
   their meanings (for methods based on your birth details, this includes results computed from them, for
   example chart placements or numerology numbers, but never your name, birth date, birth time or birthplace
   themselves); any follow-up questions you ask about that reading; the language you use; and, for
   Palmistry only, your palm photo. The "Test key" button sends one tiny request containing no reading data.
   We do not operate any proxy: the request goes from your phone straight to the provider, using your key, and
   usage is billed to your own account with them.
2. **Birthplace search.** When you type a city for a birthplace, the text you type (two or more characters) is
   sent to Apple Maps (MapKit) to find matching places. Apple handles it under its own terms.
3. **Speech recognition.** If you use the microphone button, Apple's Speech framework runs on your device only.
   The app requires on-device recognition and never uses a server for it. If your device cannot recognise your
   language on-device, the button is shown as unavailable.

Nothing else is transmitted by the app. The Lantern hints are always generated on the device (or are fixed
text bundled in the app), even if you have switched on cloud narration. When you tap a link such as
"Get a key at ..." or an acknowledgements link, you leave the app for that website, which has its own policy.

## What we never do

- No accounts or sign-in.
- No advertising and no ad networks.
- No analytics or crash-reporting libraries inside the app, and no tracking across apps or websites.
- No selling, renting or sharing of your data. We do not receive it in the first place.
- No in-app purchases.

(Apple may give developers aggregated, anonymous crash and usage statistics for users who have opted in to
share them in iOS settings. This is Apple's system, not something the app collects.)

## Your controls

- **Delete your journal:** Journal screen > delete all (or remove single readings).
- **Remove a key:** Sanctum > the key section > Remove. This deletes it from the Keychain.
- **Turn cloud off:** switch off "Send readings to the cloud" in Sanctum, and narration returns to the
  on-device model.
- **Erase everything:** Sanctum > "Erase all my data" removes your birth profile, both saved API keys, your
  cloud settings and your whole journal from the phone in one step. You can also change the saved birth
  details at any time in Sanctum or in the Attune screen. Deleting the app removes its files, but iOS can keep
  Keychain items after an app is deleted, so use "Erase all my data" first if that matters to you.
- **Permissions:** you can withdraw camera, photos, microphone or speech recognition access at any time in
  iOS Settings > Mystica.

## Third parties and their policies

When you use the optional features, these companies handle data under their own terms:

- **Anthropic** (Claude): https://www.anthropic.com/legal/privacy
- **OpenAI**: https://openai.com/policies/privacy-policy
- **Apple** (Apple Maps, on-device speech, Apple Intelligence): https://www.apple.com/legal/privacy/

We do not control how long they keep the requests you send them; check their API data-retention terms.

## Retention

We keep nothing, because we receive nothing. Your data lives on your phone until you delete it. Providers you
choose to use apply their own retention.

## Children

Mystica is not directed to children under 13, and we do not knowingly collect personal information from
anyone. The app's age rating in the App Store reflects its content (occult and fortune-telling themes). If you
are a parent and believe a child entered their details into the app, they are stored only on that device and
can be deleted from the app as described above.

## Entertainment, not advice

Mystica's readings are stories told from symbols, for reflection and entertainment. They are not predictions
and are not medical, legal, financial or psychological advice.

## Changes to this policy

If the app's data handling changes (for example, if we ever add a server), we will update this page, change
the effective date above, and, where the change matters, say so in the app's release notes before the new
behaviour takes effect.

## Contact

Questions about privacy: albert_lqchen@hotmail.com
