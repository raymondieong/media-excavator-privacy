# Media Excavator Privacy Policy

Last updated: 24 November 2026

## Purpose and scope

Media Excavator finds media in the webpage you choose to scan and helps you save supported files locally. It does not operate a developer-hosted backend, advertising service, analytics service, or telemetry endpoint. This policy describes the extension and this policy page.

## Information the extension handles

While its side panel is open, the extension checks the active page and accessible embedded frames for media. It handles the page address and title; media and subtitle addresses; labels, thumbnails, language, format, duration, resolution and size; and playback data needed to match a visible player to a downloadable source. Some media addresses contain temporary access tokens.

When you download, it handles your selected quality and subtitle choices, progress, errors and cancellation state. Local history contains filenames or titles, source-page addresses, timestamps, outcomes and, when Chrome supplies it, the saved file path. The extension also remembers your theme preference.

For save-first video exports, the browser supplies a file handle for the destination you choose. That handle is stored temporarily in the extension's IndexedDB so an offscreen extension document can finish writing after you switch tabs or close the panel.

## How information is used

These data are used to discover and preview media, show available formats, retrieve and assemble supported files, add subtitles when requested, save to your chosen destination, and show download progress and local history. The extension does not read Chrome's browsing-history database or monitor unrelated browsing while its panel is closed. Existing downloads may continue after the panel or source tab closes.

## Network requests and other parties

Scanning, metadata checks, previews and downloads can request resources from the website you are viewing, its embedded players, media hosts and content delivery networks. Those hosts receive the requested address and ordinary network information such as your IP address and browser request headers. Preview and metadata requests may begin automatically while the panel is open, before you click Download.

Where needed, requests can use the browser's existing session for the source site or an appropriate referrer. The extension does not extract passwords or cookie values for transmission to the developer. Signed media URLs are used to request the media from its host, not sent to an analytics or developer server. Requests to HTTP resources are not encrypted; the source site's available protocol controls that connection.

Media processing, conversion and subtitle embedding run on your device. Files are not uploaded to a conversion service. No website content, browsing data, history or filenames are sold or shared with advertisers or data brokers. The source websites and resource hosts handle their own requests under their own privacy policies.

## Chrome Web Store Limited Use

Media Excavator’s use of information obtained through Chrome APIs complies with the Chrome Web Store User Data Policy, including its Limited Use requirements. User data are used only to provide the media discovery, preview, download, subtitle and local history features described here. The extension does not use those data for personalized advertising, sale, data brokerage, credit decisions or unrelated profiling.

## Storage, retention and your controls

The detected media list and metadata are normally held in panel memory and change as you navigate. Theme preferences and download history are stored locally through Chrome extension storage until you change or clear them, or remove the extension. Use Downloads → Clear history to remove saved history entries; Undo can restore the removed entries while that panel remains open. Clearing history does not delete downloaded files or cancel jobs.

File handles are normally deleted after an export finishes, fails or cannot start. In-progress registration and temporary request-rule data use Chrome session storage. Finished export status is kept in offscreen memory for up to five minutes. An abrupt browser or extension crash can interrupt cleanup, so temporary handles may remain until the extension's local data are removed. Temporary session data are cleared when the browser session ends.

Chrome may independently retain its native download history, browser caches and website cookies. Manage those through Chrome's settings. Delete saved files through your device's file manager. Removing the extension removes its extension storage; it does not remove files you saved. The extension does not add application-level encryption to its local storage; access is controlled by Chrome and your device.

You can close the side panel to stop discovery, cancel an active download, change Chrome's site-access permissions, clear local history, or remove the extension. Withholding site access may prevent scanning or downloads.

## Policy hosting and contact

The public version of this policy is hosted on GitHub Pages. Visiting it makes a request to GitHub, which may process normal hosting request logs under GitHub's own privacy statement. This page contains no analytics, tracking scripts, third-party fonts or embedded media.

For privacy questions, contact the maintainer through https://github.com/raymondieong/media-excavator-privacy/issues. This public repository contains the privacy policy, not the extension source. Avoid posting signed media URLs, private page addresses, credentials or file paths in public support requests.

## Policy updates

This policy will be updated when the extension’s data practices change. The date above identifies the current version. Material changes will also be disclosed through the extension as required before the changed handling begins, and reflected in the Chrome Web Store disclosures.
