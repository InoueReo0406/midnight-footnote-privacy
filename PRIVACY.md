# Privacy Policy — 夜更けの寄り道 (@midnight_footnote)

**Last updated: 2026-06-18**

## Overview

This privacy policy governs the personal video-upload automation tool ("the Tool")
operated by the owner of the YouTube channel
[夜更けの寄り道 (@midnight_footnote)](https://www.youtube.com/@midnight_footnote).
The Tool uses the YouTube Data API v3 to upload and schedule videos to the owner's own channel.

## Data Collection

The Tool **does not collect, store, or share any personal data from third parties**.

- The Tool operates solely on behalf of the channel owner (a single individual).
- No data is collected from viewers, subscribers, or any other users.
- No analytics data is stored beyond what YouTube itself provides to the channel owner.

## YouTube API Usage

The Tool uses the YouTube Data API v3 exclusively for:

- Uploading video files to the operator's own YouTube channel
- Setting video metadata (title, description, tags, category)
- Scheduling video publication via `publishAt`
- Setting custom thumbnails via `thumbnails.set`

All API calls are made using OAuth 2.0 credentials belonging to the channel owner.
No OAuth tokens are shared, sold, or disclosed to any third party.

## Data Retention

- OAuth refresh tokens are stored locally on the operator's own machine and are never published.
- No credentials or personal data are exposed in this repository.

## Contact

For questions about this privacy policy, contact: `reo.inoue.biz@gmail.com`
