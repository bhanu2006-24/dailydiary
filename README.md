# 📖 Daily Diary — Private Digital Journal

A realistic, skeuomorphic, and privacy-focused digital diary application designed to provide the tactile feel of writing in a personal leather-bound notebook with the convenience of modern web features.

100% offline-first. All entries, photos, and configurations are stored securely inside your browser using IndexedDB. No external servers, no cloud tracking.

---

## ✨ Features

- **Realistic 3D Book Experience**: Tactile book cover with embossed gold lettering, stitched edge details, realistic 3D open/close flip animations, and satin ribbon bookmark.
- **5 Aesthetic Themes**:
  - *Classic Leather*: Traditional warm saddle-leather notebook with aged gold details.
  - *Vintage Antiquity*: Earthy aged parchment and walnut cover.
  - *Minimal Slate*: Clean, modern Nordic slate aesthetic.
  - *Sakura Pink*: Soft blush tones and delicate floral charm.
  - *Midnight Dark*: Deep dark velvet theme for evening journaling.
- **Authentic Paper Styles**:
  - *Ruled / Lined*: Authentic notebook ruling aligned with font line-height.
  - *Dotted Grid*: Bullet-journal style subtle grid.
  - *Blank Parchment*: Clean texture for freeform writing.
- **Rich Stationery & Formatting**:
  - Fonts: Serif (*Lora*), Sans (*Inter*), Handwriting (*Caveat*), Cursive (*Dancing Script*), Typewriter (*Courier New*).
  - Pen Inks: Fountain Pen Black, Royal Blue, Burgundy, and Forest Green.
  - Highlighters: Canary Yellow, Blossom Pink, and Spearmint Green.
  - Subheadings (H2), bold, italic, underline, strikethrough, blockquotes, divider lines, and bullet/numbered lists.
  - Photo attachments with inline preview stored directly in IndexedDB.
  - Decorative stamps & stickers (🌸, ✨, ❤️, ⭐, 🌿, ☕, 📖, 🌙).
- **Interactive Calendar Archive**:
  - Monthly view highlighting days with written memories.
  - Jump directly to any past entry or start a new entry for any selected date.
- **Deep Full-Text Search**:
  - Instant real-time search across titles, dates, mood tags, and full body text with highlighted search snippets.
- **Bookmark & Favorites**:
  - Click the satin ribbon bookmark to flag favorite entries.
- **Flexible Export & Backup**:
  - **PDF Export**: Generates a clean, archival-grade formatted PDF document complete with title, date, mood, and content.
  - **Markdown (.md) Export**: Export individual entries into clean Markdown.
  - **Full JSON Backup & Restore**: Export all entries, settings, and base64-encoded images to a single JSON file for offline backups and device transfers.

---

## 🚀 Getting Started

Daily Diary requires **no installation, no npm packages, and no build step**.

### Option 1: Open Directly in Browser
Simply double-click `index.html` or drag it into any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Static Server
If you prefer running a local server:

Using Python:
```bash
python3 -m http.server 8080
```
Then navigate to `http://localhost:8080` in your browser.

Using Node (`npx`):
```bash
npx serve .
```

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl` / `Cmd` + `S` | Save current entry immediately |
| `Ctrl` / `Cmd` + `N` | Create a new blank diary page |
| `Ctrl` / `Cmd` + `F` | Open memory search |
| `Escape` | Close modals / stationery drawer / close diary |

---

## 🔒 Privacy & Data Architecture

- **100% Client-Side**: All data is stored in the browser's `IndexedDB` (`PersonalDiaryDB`).
- **No Analytics / Telemetry**: Zero network requests for your content.
- **Portability**: Take full ownership of your memories using the JSON Backup & Restore tools in Diary Settings.

---

## 🛠️ Tech Stack

- **HTML5** & **Vanilla JavaScript** (ES6 modules and IndexedDB API)
- **Tailwind CSS** (via CDN) & Custom CSS3 animations
- **html2pdf.js** (client-side PDF generation)
- **FontAwesome 6** & **Google Fonts**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to customize and enjoy your journaling journey!
