---
lang: en
title: Privacy Policy
permalink: /en/privacy/
alt: /privacy/
description: What information the Easy NAS Player LG TV app handles, where it is stored and where it connects.
---
# Privacy Policy

<p class="meta">Effective: October 27, 2026 (1.0.0)</p>

**Easy NAS Player** (the "App") is a free LG webOS TV app for viewing photos and videos stored on your own Synology NAS. The App sends no information to the developer.

## 1. Information the developer collects
None. The App has no developer server and contains no analytics, advertising, tracking or crash-reporting tools.

## 2. Information stored only on your TV
To work, the App stores the following inside your TV (in the App's storage). It is never sent off the TV.

| Information | How it is stored |
|---|---|
| NAS connection details (name, address or QuickConnect ID, port, HTTPS on/off, "ignore certificate errors" on/off, account name, start folder) | App storage |
| NAS password and, if you enter one, the two-factor (OTP) authenticator key | **Encrypted** with an AES-256 key created by webOS keymanager3 that only this App can use. If encryption is not available, it is not saved and is kept in memory only while the App runs |
| Two-factor "trust this TV" device token | App storage |
| Settings (theme, view, subtitle style, etc.), recent folders, video resume positions | App storage. Recent folders and resume history can be cleared in Settings > Data |
| Diagnostics log (last 100 requests to the NAS) | In memory only while the App runs. Session IDs, passwords, codes and device tokens are masked; the log is gone when the App closes |

## 3. Where the App connects
- **The NAS you register** — for sign-in, folder lists, thumbnails, photos, videos and subtitles. Your account name, password and verification code are sent only to this NAS when signing in.
- **Synology QuickConnect servers** — only when a profile uses a QuickConnect ID: the App sends that ID to Synology's QuickConnect server (global.quickconnect.to) to find your NAS, then connects to the address Synology returns (a Synology relay server if needed). This is governed by Synology's privacy policy.
- The App's built-in JS service listens only inside the TV (127.0.0.1) and only carries the connections above.
- The App's UI framework (LG Enact Limestone) is set up to download a font file from Google Fonts (fonts.gstatic.com) only if the TV lacks its built-in font. That request contains none of the information the App stores.

## 4. Sharing, advertising and tracking
None. We do not sell or share personal information with third parties and do not use advertising identifiers.

## 5. Retention and deletion
Data stays on your TV until you remove it or delete the App. Deleting a profile also deletes its password and authenticator key. "Sign out" on the folder screen keeps the profile but deletes its password, authenticator key and trusted-device token. **Deleting the App deletes the data it stored on the TV.**

## 6. Children
The App is not directed to children and does not knowingly collect children's information.

## 7. Changes
If this policy changes, the new version will be posted on this page with a new effective date.

## 8. Contact
- Developer: JJ Labs
- Email: [jjlab-support@googlegroups.com](mailto:jjlab-support@googlegroups.com)
- Support page: [Support]({{ '/en/support/' | relative_url }})

Synology, DSM and QuickConnect are trademarks of Synology Inc. This App is not affiliated with Synology Inc.
