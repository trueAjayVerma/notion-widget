# Notion Enhanced Widgets 🚀

Two elegant, theme-aware widgets for Notion that automatically adapt to light/dark mode:
1. **Smart Countdown Timer** ⏳
2. **Live Date & Time Display** 🕒

## ✨ Features

- **Seamless Notion Integration**  
  Embeds perfectly in Notion's desktop/mobile apps
- **Auto Theme Detection**  
  Matches Notion's light/dark mode with smooth transitions
- **Customizable**  
  Adjust via URL parameters - no code editing needed
- **Privacy Focused**  
  No tracking, no external dependencies

## 🛠️ Installation

1. **Host the files**:
   - Upload both HTML files to [GitHub Pages](https://pages.github.com/), Vercel, or Netlify
   - (Recommended) Create a dedicated `widgets` repo

2. **Embed in Notion**:
   ```markdown
   [Countdown](https://yoururl.com/countdown.html?date=2024-12-31T23:59&title=New%20Year)
   [Clock](https://yoururl.com/clock.html)
Use Notion's /embed block and paste the URL

🎯 Widget Usage
⏳ Countdown Timer
URL Parameters:

Parameter	Example	Description
date	2024-12-31T23:59	Target date/time (ISO format)
title	Project%20Deadline	Custom title (URL-encoded)
Example:
countdown.html?date=2024-06-15T17:00&title=Release%20Date

🕒 Live Clock
URL Parameters:

Parameter	Example	Description
format	12	Optional: 12 or 24 hour format
Example:
clock.html?format=12
