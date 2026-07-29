# VidMG Privacy Policy

**Effective date:** July 29, 2026  
**Product:** VidMG — Drive Screen Recorder (Chrome extension)  
**Contact:** `rahulverma212131@gmail.com`

> **Short version:** VidMG records on your device and saves videos to **your** Google Drive. There is no VidMG cloud that stores your recordings, passwords, or Google access tokens.

## 1. Who we are

VidMG is a Chrome extension for Loom-style screen recording. Videos are stored in a **VidMG Recordings** folder on the signed-in user’s Google Drive.

## 2. Data we access

| Data | Purpose |
|------|---------|
| Google name, email, profile picture | Show signed-in account in the UI |
| Google Drive files **created by VidMG** (`drive.file`) | Upload, list, rename, delete, share recordings |
| Screen / window / tab / camera / microphone | Only while you record, after Chrome prompts |
| Local extension storage | Sign-in display info + VidMG folder id |

## 3. How we use data

- Sign in with Google (Chrome Identity API)
- Upload/manage recordings in your Drive
- Sharing you explicitly start (private, public link, or email invite)
- Display your account in the popup/library

We do **not** sell personal data, use recordings for ads, or use Google user data to train third-party AI models.

## 4. Where data is stored

- **Recordings:** your Google Drive
- **Pending uploads:** temporary on-device IndexedDB, then removed
- **OAuth tokens:** on-device via Chrome / extension service worker
- **VidMG servers:** none

## 5. Sharing

New recordings are private by default. If you enable **Anyone with the link**, anyone with the URL can view. Email invites grant access to specific Google accounts.

## 6. Limited Use disclosure

VidMG’s use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google user data is used only to provide or improve prominent user-facing features (recording, Drive storage, library, sharing you initiate). It is not sold and not transferred for advertising.

## 7. Permissions

- `identity` — Google sign-in  
- `storage` — local preferences / profile cache  
- `tabs` / `windows` — open recorder & library  
- Hosts: `googleapis.com`, `accounts.google.com` only  

## 8. Retention & deletion

Delete files in VidMG or Drive. Sign out clears local cache and revokes the cached token when possible. Uninstall removes local extension data; Drive files remain until you delete them.

## 9. Children

Not directed to children under 13.

## 10. Changes

We may update this policy; the effective date will change.

## 11. Contact

`rahulverma212131@gmail.com`
