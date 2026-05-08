# Sovereign-Coffee Roast Log
A zero-dependency, local-first, offline HTML/JS application for logging &amp; tracking home coffee roasting profiles. Designed specifically with a Behmor 1600/2000AB drum roasters in mind, but adaptable to any manual roasting setup.

## The Philosophy
Modern coffee roasting apps are bloated cloud services that require subscriptions, internet connections, and web accounts, acting as data-harvesting tools for corporate entities. 

The **Sovereign-Coffee Roast Log** rejects this model. 
* **No Cloud:** It runs entirely on your local machine.
* **No Subscriptions:** It is a single, standalone HTML file.
* **Total Ownership:** Your coffee, your hardware, your data.

## Features
* **Single-File Architecture:** Just open `index.html` in any web browser. No local servers, node modules, or installations required.
* **Persistent Local Storage:** Saves your roast data securely to your browser's `localStorage`.
* **Printable 4-Up Placards:** Select multiple roasts and generate formatted, multi-page, physical physical cards designed perfectly to be cut into 4-up placards for organizing your bean cellar or printing to labels for your bags.
* **Star Rating System:** Instantly verify your best roasts at a glance.
* **JSON Export/Import:** Full database backup and restore capabilities ensure you never lose your data when changing computers or clearing browser history.

## How to Use

1. **Run the App:** Double-click `index.html` to open it in Chrome, Firefox, Edge, or Safari.
2. **Log a Roast:** Enter your bean origin, date, power profiles, and development times. Hit "Save to Log".
3. **Print Placards:** Select the checkboxes next to the roasts you want physical cards for. Click "Print Selected". 
   * *Printing Tip:* Ensure your printer dialog is set to **Scale: 100% / Default** and **Margins: Minimum/None** so the CSS grid prints exactly 4 cards per 8.5"x11" sheet.
4. **Backup Your Data:** Click **Export DB** to download a `.json` backup of your entire roasting history. Do this regularly. 

## Data Portability (Backups)
Because this app relies on `localStorage`, your data is tied to the specific file path on your computer. 
1. Place the `index.html` file in a permanent folder (e.g., `Documents/Coffee/`).
2. If you accidentally clear your browser data or move to a new PC, simply click **Import DB** and select your latest `.json` backup file to restore your entire history.

## License
This project is licensed under the MIT License. Free to use, modify, and distribute.

## Privacy
Everything is 100% local to your machine and absolutely no data is ever collected!

## Tip Jar
If you like this project and find it useful, consider sending me a coffee: willingjade746@walletofsatoshi.com Thank you!

