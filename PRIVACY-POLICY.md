# Privacy Policy — Smooth Cache for Kodik

**Effective date:** October 13, 2026

## Information stored on your device

Smooth Cache for Kodik stores HLS media segments received from a compatible Kodik player so that the player can reuse those segments during playback. The cache is kept in IndexedDB in the browser profile on your device. Its records may include segment data, stream or segment URLs, technical cache metadata, and storage and expiration times. Stream URLs may contain parameters supplied by the stream provider.

The extension also stores your settings, selected interface language, and recent technical playback/cache status in the browser's local extension storage. This status may include cache and buffer counters, HLS detection, an error message, an update time, and a local browser tab identifier.

## Data transmission

The extension does not send cached media, settings, viewing history, or diagnostics to its publisher. It does not include analytics, advertising trackers, or an account system. To play and cache a stream, the player and extension make requests to the player and to the media hosts identified by that stream's HLS playlist. Those requests are sent to the respective service providers and are subject to their policies.

## Permissions

The extension uses browser storage for local settings and status. It runs in compatible Kodik player frames on `kodikplayer.com` and its subdomains to detect HLS playlists and reuse or cache stream segments. It does not request access to the websites that embed the player.

## Retention and deletion

The cache size limit and retention period can be changed in the extension settings. The default retention period is three days; the default cache size limit is 3 GB. Expired records are removed during cache maintenance, and older records may be evicted when the configured size limit is reached. You can clear the cache from the extension popup. You can also remove the extension's local settings in Edge or clear site data for the player origin. Because the media cache is stored under the player origin, uninstalling the extension may not remove that IndexedDB data automatically.

## Changes to this policy

This policy may be updated when the extension's behavior changes. The effective date above identifies the latest version.

## Contact

For privacy questions, open an issue in this repository: <https://github.com/Dororo367/smooth-cache-for-kodik-privacy/issues>. Issues are public; do not include passwords, private URLs, or other sensitive information.

