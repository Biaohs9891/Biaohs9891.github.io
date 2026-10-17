# Daily Expenses

A simple, private expense tracker for everyday household spending in Pakistani rupees (PKR). It works offline and keeps all data on your own phone.

## Features

- Login screen. The first login is `Admin` / `admin`, and the app asks you to choose your own username and password straight away. You can change them again later in Settings.
- Dashboard for any month: net amount, amount spent, remaining balance, spent and remaining percentages, and a bar for each main item with its share of spending.
- Expense entry with item, amount, date and an optional note.
- Net amount entry with date. You can edit or delete it later.
- Item list with common household items (Milk, Vegetables, Eggs, Flour, Gas, Committee (Kameti), Internet Bill, Mobile Package, Clothes, Groceries and more). You can add or remove items. Cigarettes always stays at the end of the list.
- Export all data to a CSV file.
- Works offline and can be installed on your phone as an app.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app (layout, styles and code) |
| `manifest.json` | App name, colours and icons for installing |
| `sw.js` | Service worker that lets the app work offline |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Put it online with GitHub Pages

1. Upload all the files to the main folder of a repository.
2. Go to **Settings, then Pages**.
3. Set **Source** to **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save.
4. After a minute or two, your link appears at the top of the Pages screen.

## Install on Android

**Option 1: From Chrome.** Open your link in Chrome, tap the menu (⋮), then **Install app** or **Add to Home Screen**.

**Option 2: As an APK.** Paste your link into [pwabuilder.com](https://www.pwabuilder.com), tap **Package for stores**, choose **Android**, and generate the package. Install the signed `.apk` from the downloaded ZIP. For the app to open full screen without a browser bar, the site must be hosted at the root of a domain, such as `yourusername.github.io`, with the `assetlinks.json` file from the ZIP placed in a `.well-known` folder.

Keep the signing key file and its password from the ZIP somewhere safe. You need them to update the app later.

## Privacy and security

- All data is stored only in your phone's browser or app storage. Nothing is sent to any server.
- The password is stored as a hash, but the login only locks the app on your device. It does not encrypt your data.
- If you uninstall the app or clear its storage, your data is deleted. Use **Export CSV** in Settings to keep a backup.
