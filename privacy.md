# Privacy Policy

Effective date: July 9, 2026

Local Page Media Downloader is a local, user-triggered Chrome/Chromium extension for finding media URLs that are already visible or accessible to the active browser tab.

## Data collection

The extension does not collect, sell, share, transmit, or store personal data on external servers.

The extension reads the active page only after the user clicks the scan button. It may inspect page HTML, media element attributes, CSS background URLs, metadata media tags, direct media links, and browser resource timing entries for the active tab. This processing happens locally in the browser.

## Data use

The extension uses discovered media URLs only to show them in the popup and, when the user clicks the download button, to ask the browser downloads API to download selected items.

The extension does not run automatic background scans. Downloads never start automatically.

## Data sharing

No discovered URL, browsing activity, page content, setting, or download list is sent to a developer-operated server, analytics service, advertising network, or third party.

## Local settings

The extension may store local popup settings, such as the minimum media size filter and whether unknown-size media should be shown. These settings are stored locally in the browser.

## Remote code, telemetry, and analytics

The extension does not use remote code, telemetry, analytics, tracking pixels, or external scripts.

## Permissions

- `activeTab`: grants temporary access to the currently active tab after the user interacts with the extension.
- `scripting`: runs the local scan function in the active tab only after the user clicks scan.
- `downloads`: downloads selected media only after the user clicks download.

The extension does not request broad host permissions.

## Limited use statement

The use of information received from browser APIs will adhere to applicable browser extension user data policies, including limited use requirements.

## Legal note

Users are responsible for respecting copyright, licenses, website terms, and applicable law. The extension does not bypass DRM, authentication, paywalls, copyright protections, or protected streaming mechanisms.

## Contact

For support, feedback, or collaboration, contact [mekvian@proton.me](mailto:mekvian@proton.me).

GitHub: [mekvian](https://github.com/mekvian).
