# VOMYTZoomAutomation
Internal YouTube Uploader
Description:
This application is a private, internal-use tool designed solely for the owner’s YouTube channel. It automates the process of uploading internal videos (e.g., Zoom meeting recordings) to the channel for archival and personal reference.

Purpose & Audience
Audience: Only the owner of the YouTube channel and authorized collaborators.
Not for Public Use: The app is not published publicly, not distributed to external users, and not intended for anyone outside the authorized owner’s team or organization.
How It Works
OAuth Authorization:
The app requires the user (channel owner) to sign in with their Google account and grant permission to upload videos to their own YouTube channel.

YouTube Data Access:

Scope: youtube.upload for uploading videos.
No other personal data is accessed.
The app uploads videos directly to the authenticated channel and does not share data with any third parties.
Data Storage & Security:

No permanent user data is stored beyond what is needed for authentication (access/refresh tokens).
Tokens are kept securely and are not shared.
Uploaded videos remain on the owner’s YouTube channel and are not visible to the public unless the owner changes their privacy settings.
Privacy & Control:

The channel owner can revoke access at any time through their Google Account settings.
Since this is for internal, personal use, no additional users or data sources are involved.
Verification Notes
This application does not need to be published to the public.
Verification is requested solely to allow the channel owner to use the API for their own channel uploads.
No external users will encounter the OAuth consent screen beyond the owner or authorized team members.
