# Pozzo Toys

One installable app with two pages. Swipe left and right, or tap the tabs.

## Sales Tracker (`orders.html`)

1. Paste an order confirmation message and tap **Read message**.
2. Check every field. Warnings appear when the message total is 0 or does not match.
3. Tap **Confirm & save**. The order is added to that month's Google Sheet, and the sheet assigns the order ID.
4. **Generate next parcel file** builds the parcel entry Excel from the sheet. **Generate range** builds a chosen range.

## Sticker Builder (`stickers.html`)

1. Tap **Choose label PDF** and select the Steadfast labels.
2. Check each parcel against the label picture and fix any wrong field.
3. Tap **Download Excel** for the parcel tag file.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The app screen with both pages |
| `orders.html` | Sales Tracker |
| `stickers.html` | Sticker Builder |
| `manifest.webmanifest` | Lets the app be installed |
| `sw.js` | Keeps the pages and libraries ready |
| `icon-192.png`, `icon-512.png` | App icons |

## Updating

Upload the changed files to this repository and commit to main. Open the app twice to load the new version.

## Privacy

Label PDFs are read on the phone and never uploaded. Orders go only to your own Google Sheet.
