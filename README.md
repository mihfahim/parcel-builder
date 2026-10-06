# Pozzo Toys Parcel Sticker Builder

A phone web app that reads Steadfast courier label PDFs and builds the parcel tag Excel file.

## How to use

1. Open the app link in Chrome and choose **Install app** (or **Add to Home screen**).
2. Tap **Choose label PDF** and select the Steadfast labels.
3. Check each parcel card against the label picture. Fix any field that is wrong, especially Bangla names and addresses.
4. Untick parcels you do not want to include. Duplicates and ৳0 COD parcels are flagged.
5. Tap **Download Excel**. To share the file, open it from your Downloads or Files app and use that app's share button.

## Output

Excel file with five columns: Parcel ID, COD Amount, Customer Name, Phone Number, Delivery Address.
File name: `Parcel tag (date) PZ (serial).xlsx`

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The app |
| `manifest.webmanifest` | Lets the app be installed on the phone |
| `sw.js` | Saves the app libraries for faster loading |
| `icon-192.png`, `icon-512.png` | App icons |

## Updating

Upload the new `index.html` to this repository and commit. Open the app twice to load the new version.

## Privacy

Label PDFs are read on the phone. They are not uploaded anywhere.
