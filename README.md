# Lead Tracker – Chrome Extension

**Lead Tracker** is a simple Chrome extension that lets you save interesting websites (leads) — either with one click from your current browser tab or by entering URLs manually. All links are saved locally and can be accessed anytime.

![Screenshot](icon.png)

## Features

- 📌 Save the current tab’s URL with one click
- 📝 Manually add any URL you like
- 📂 Display saved leads as clickable links
- 🗑️ Clear all saved leads with a single button
- 💾 All data is stored locally in your browser (via `localStorage`)

## Installation

1. Download and unzip the extension files.
2. Open Chrome and go to `chrome://extensions/`.
3. Enable **Developer mode** (top right).
4. Click **Load unpacked**.
5. Select the folder containing the extension files.
6. The extension icon will appear in your toolbar.

## Project Structure

```bash
├── index.html          # Popup HTML
├── index.css           # Styling
├── index.js            # Functionality (JavaScript)
├── manifest.json       # Chrome Extension config
├── icon.png            # Extension icon
├── vite.config.js      # Build config (Vite)
└── package.json        # npm project file
