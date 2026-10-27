---
lang: en
title: Support
permalink: /en/support/
alt: /support/
description: Help and contact information for the Easy NAS Player LG TV app.
---
# Support

## Contact
Email: [jjlab-support@googlegroups.com](mailto:jjlab-support@googlegroups.com)

When reporting a problem, please tell us what you did, what you expected and what actually happened, along with the app version (Settings › About), TV model, webOS version, NAS model and DSM version. **Never send your NAS password, verification codes or authenticator key.**

## Getting started
1. Open the app and press **+** (Add NAS) on the NAS list.
2. Enter the NAS address (IP or domain) or QuickConnect ID, port, HTTPS on/off, account name and password, then select **Save and connect**.
3. Open a shared folder to view photos and videos. In Settings (gear icon) you can change the theme, view, playback method and subtitle style.

Requirements: a Synology NAS running DSM and an account that can use File Station. Video Station streaming requires Video Station on the NAS.

## FAQ

### Where is my password stored?
Only on your TV. The password and authenticator key are encrypted with a key only this app can use, and are never sent to the developer. **Sign out** on the folder screen keeps the profile but deletes the saved password, authenticator key and trusted-device token. See the [Privacy Policy]({{ '/en/privacy/' | relative_url }}) for details.

### Does it work with two-step verification?
Yes. Enter the verification code when signing in and choose **Trust this TV** to skip it next time. If you add your authenticator key to the profile, codes are filled in automatically.

### Can I connect to my NAS from outside my home?
Yes, using your NAS's external address (domain) or a QuickConnect ID. With a QuickConnect ID, the app sends that ID to Synology's QuickConnect server to find your NAS.

### I get a certificate error.
If your NAS uses a self-signed certificate, turn on **Ignore certificate errors** in the profile. Only do this for a NAS you trust.

### Some videos don't play.
Direct playback supports only the codecs your TV supports (for example H.264 / HEVC with AAC / AC3 / MP3). If Video Station is installed on your NAS, set **Playback method** in Settings to Video Station to play a stream converted on the NAS.

### Subtitles don't show.
Put the subtitle file in the same folder with the same name as the video (for example `movie.mp4` and `movie.srt`). .srt, .smi and .vtt are supported.

### How do I set a folder cover?
Put `cover.jpg` or `folder.jpg` (or .png) inside the folder and it is shown as the folder's cover.

### Can I upload or delete files?
No. The app is view-only; it never uploads, modifies or deletes files on your NAS.

### Is the app free?
Yes. There are no ads and no in-app purchases.

Easy NAS Player is not affiliated with Synology Inc. Synology, DSM and QuickConnect are trademarks of Synology Inc.
