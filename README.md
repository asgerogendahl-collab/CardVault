# CardVault

CardVault is a mobile-friendly football trading card collection manager.

## Features
- Add cards with player, club, manufacturer, set, card type, numbering and estimated value.
- Upload a card photo.
- Search and filter your collection.
- Browse a local card catalogue and add catalogue cards to your collection.
- Export and import a JSON backup.
- Responsive dark-and-gold design.

## Run locally
Open `index.html` in a modern browser.

## Deploy with Vercel
1. Sign in to Vercel.
2. Choose **Add New → Project**.
3. Import `asgerogendahl-collab/CardVault` from GitHub.
4. Leave the framework preset as **Other** and the build command empty.
5. Set the output directory to `.` (or leave the default if detected).
6. Deploy.

## Important prototype notes
This version stores collection data in the browser's local storage. It does not yet provide real user authentication, cloud sync, shared community data, or cross-device storage. Use the backup export to keep a copy of your collection.