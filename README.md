## Pixeldrain Bypass Limit Enhanced — ZIP & Gallery Support

**Description**  
Bypass Pixeldrain download limits using multi-proxy API support (cached 24h). Supports individual file downloads, gallery downloads, and ZIP downloads for entire galleries. Adds vertical **Download DL all files** and **Show DL all files** buttons on gallery pages. Bypass links open in new tabs and can be copied or saved as text files.

**Features**
- Bypass download limits via API-provided proxies (randomized).
- 24‑hour proxy list cache to improve reliability.
- Single file (`/u/`) and gallery (`/l/`) support.
- Download entire gallery as ZIP via proxy (`/zip/<id>`).
- Vertical gallery buttons: ⬇️ **Download DL all files** and 🔗 **Show DL all files**.
- Popup to copy or save all bypass URLs.
- Opens bypass links in new tabs (or via GM_openInTab when available).
- Works with common Pixeldrain domains and CDN embeds.

**Instructions**
1. Install in Tampermonkey or a compatible userscript manager.
2. Open a Pixeldrain file page (`/u/<id>`) or gallery page (`/l/<id>`).
3. Click **Download Bypass** to open the bypassed file in a new tab.
4. On gallery pages, use **Download DL all files** to get the ZIP, or **Show DL all files** to view/copy/save individual bypass links.
5. Use the popup buttons to copy links to clipboard or save them as a `.txt` file.

**Notes**
- Proxy list is fetched from an API and cached in `localStorage` for 24 hours. You can clear localStorage to force an immediate refresh.
- The script prefers `GM_openInTab` if available; otherwise it falls back to `window.open`.
- No personal data is collected by the script.

**Author / Support**
- Author: GameDrive.Org  
- Homepage: https://greasyfork.org/users/1290286
