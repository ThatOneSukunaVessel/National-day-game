# DAYQUEST — A New Celebration Every Day

Playable, responsive browser game about the daily national/fun observance.

## How to play
- Double-click `index.html` to open in Chrome, Edge, Firefox or Safari.
- The home screen automatically detects your device's current calendar date.
- Click **Play Today's Challenge**. Catch positive celebration icons; avoid bombs. There are three increasingly fast waves in each 45-second run.
- Claim one daily reward, build a daily claim streak, earn coins, unlock cosmetic orb styles, and see progress and achievements.
- Explore the calendar to see celebrations on other dates. Save data is stored automatically in localStorage in that browser.

## Publish to GitHub Pages
1. Create a GitHub repository, or place DAYQUEST in its **own** new folder/repository.
2. Upload `index.html` to the repository root (the README is optional).
3. Under **Settings > Pages**, select **Deploy from a branch**, your `main` branch, and `/ (root)`, then **Save**.
4. Open the GitHub Pages URL when GitHub finishes publishing.

## Daily updates
- Featured celebration and challenge theme change at **midnight in the player's device's local timezone**, even if the tab is kept open.
- The complete observance calendar (all 366 month/day combinations) is loaded from the public domain (CC0) dataset by James Campbell at https://adayisaholiday.com/holidays.json via GitHub's public raw file `https://raw.githubusercontent.com/james-see/everydayisaholiday/main/docs/holidays.json`.
- Once successfully downloaded, the data is cached in your browser for offline use. Some built-in highlights, including National Cat Day (October 29), work right away even without an internet connection.
- National Day names are generally informal US or worldwide observances, not necessarily legal public holidays. Observances can vary among calendars and countries. The external dataset is curated and can contain errors.

No install, accounts, server, API key, or build tools required. Google Fonts load online; local fallback fonts work offline.
