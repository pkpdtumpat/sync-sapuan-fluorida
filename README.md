# Sync Sapuan Fluorida ke Sheets — Privacy Policy / Dasar Privasi

**Disclaimer / Penafian:**
This is an independent, unofficial productivity extension developed to assist dental clinic personnel. It is not affiliated with, endorsed by, or developed by the Ministry of Health Malaysia (KKM).

## Data Collection & Usage (Pengumpulan & Penggunaan Data)
1. **Local Browser Processing:** All patient records extracted from the active webpage table are processed 100% locally within the user's Chrome browser.
2. **Google Drive & Sheets Access:** Using the official Chrome Identity API (`drive.file` scope), the extension creates and updates spreadsheets exclusively inside the user's own Google Drive (`Sync Kohort FV` folder).
3. **No Third-Party Servers:** No patient data, personal identifiable information, or Google account tokens are transmitted to, stored on, or shared with any external or third-party servers.
4. **Local Preferences:** User settings (WhatsApp message templates, TCA alert thresholds, and linked spreadsheet IDs) are stored solely within Chrome's built-in storage (`chrome.storage`).

## Contact / Hubungi Pembangun
For support or inquiries, contact: `syncfvtosheets@gmail.com`

Effective Date / Tarikh Kuat Kuasa: November 2026

---

## Changelog / Log Perubahan

### v1.2 (November 2026)
- **Simplified OAuth Scope (`drive.file`):** Removed the broad `spreadsheets` scope so new users no longer encounter the *"Google hasn't verified this app"* warning screen or the 100-user OAuth cap, while preserving full sync compatibility with existing spreadsheets.
- **WhatsApp Desktop Emoji Fix:** Switched desktop hyperlink generation from `wa.me` to `api.whatsapp.com/send` with `ENCODEURL` formatting to prevent UTF-8 emoji corruption (``).

### v1.1 (November 2026)
- Initial public release on Chrome Web Store with Google Drive `Sync Kohort FV` folder integration, Smart Merge, `W1`/`W2` checkboxes, and `NEXT TCA` early warning highlights.
