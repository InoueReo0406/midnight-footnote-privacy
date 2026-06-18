# Privacy Policy — 夜更けの寄り道 (@midnight_footnote)

**Last updated: 2026-06-18**

## Overview

This privacy policy governs the personal video-upload automation tool ("the Tool")
operated by the owner of the YouTube channel
[夜更けの寄り道 (@midnight_footnote)](https://www.youtube.com/@midnight_footnote).
The Tool uses the YouTube Data API v3 to upload and schedule videos to the owner's own channel.

## YouTube API Services

The Tool uses **YouTube API Services**. By using the Tool, you are agreeing to be bound by:

- The [YouTube Terms of Service](https://www.youtube.com/t/terms)
- The [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service)

The Tool's use and transfer of information received from YouTube / Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

### Google Privacy Policy

This Tool relies on Google services. Please also review the
**[Google Privacy Policy](https://policies.google.com/privacy)**, which describes how Google
handles data across its services.

## Data Collection

The Tool **does not collect, store, or share any personal data from third parties**.

- The Tool operates solely on behalf of the channel owner (a single individual).
- No data is collected from viewers, subscribers, or any other users.
- No analytics data is stored beyond what YouTube itself provides to the channel owner.

## What Data the Tool Accesses

The Tool uses the YouTube Data API v3 exclusively for the channel owner's own channel:

- Uploading video files (`youtube.videos.insert`)
- Setting video metadata (title, description, tags, category)
- Scheduling video publication via `publishAt`
- Setting custom thumbnails (`thumbnails.set`)

Authentication uses OAuth 2.0 credentials belonging to the channel owner. The only stored
credential is an OAuth **refresh token**, kept locally on the operator's own machine. No OAuth
tokens or accessed data are shared, sold, or disclosed to any third party.

## Data Retention and Deletion

- The OAuth refresh token is stored only on the operator's local machine and is never published.
- **Deletion / revocation:** The channel owner can revoke the Tool's access at any time at
  [Google Account → Third-party access](https://myaccount.google.com/permissions). Revoking
  access immediately invalidates the stored token. The local token can also be deleted by
  removing it from the local environment file.
- No personal data is retained on any server, because the Tool runs entirely locally and
  operates a single account.

## Changes to This Policy

This policy may be updated; the "Last updated" date above reflects the latest revision.

## Contact

For questions about this privacy policy, contact: `reo.inoue.biz@gmail.com`
