# Privacy Policy for Hattrick xPoints Column

**Last Updated:** November 25, 2026

## 1. Overview
**Hattrick xPoints Column** is a browser extension that calculates and displays Expected Points (xP) and Expected Goals (xG) in Hattrick league tables using official CHPP match replay statistics. Your privacy is important to us, and this extension is designed to operate entirely within your browser without any external developer servers.

## 2. Data Collection and Usage
This extension does **not** collect, transmit, store, or sell any personal data to the developer or any third parties.

To function properly, the extension handles the following data locally on your device:
* **Hattrick CHPP OAuth Tokens (`accessToken` and `accessTokenSecret`):** Obtained via the official Hattrick OAuth 1.0a authentication flow (`chrome.identity`) when you connect your account. These tokens are stored strictly locally in `chrome.storage.local` and are used solely to authenticate API requests to `chpp.hattrick.org`.
* **Match Simulation Cache:** Match probabilities and expected goal figures fetched from the Hattrick CHPP API are cached locally in `chrome.storage.local` to improve performance and minimize API requests.
* **User Preferences:** Your selected interface language (`uiLang`) is stored locally in `chrome.storage.local`.

## 3. Third-Party Services
The extension communicates exclusively with official Hattrick domains (`*.hattrick.org` and `chpp.hattrick.org`) to read league table pages and retrieve match statistics via the CHPP API. No analytics, tracking scripts, or third-party servers are used.

## 4. Data Control and Deletion
You maintain full control over all locally stored data:
* You can clear cached match data at any time using the **"Clear Match Cache"** button inside the extension popup.
* Revoking application access in your Hattrick account settings or uninstalling the extension permanently deletes all stored tokens and local data from your browser.

## 5. Contact
If you have any questions regarding this Privacy Policy or the extension, please contact the developer via the Chrome Web Store support tab or the project's GitHub repository.