# Money Hunter AI — starter prototype

This is a phone-friendly web prototype for the planned Android app. It can be hosted as a simple website and may be installable as a PWA when served over HTTPS.

## Included
- Deal/resale profit calculator
- eBay UK and Facebook Marketplace search links
- Saved deal shortlist
- Bank-switch offer tracker and checklist status
- Cashback/reward tracker
- Scrap return calculator using user-entered verified prices
- Bitcoin/Solana signal checklist (manual, no live feed)
- Transaction ledger and JSON export
- Browser-local storage

## Important limitations
- This is not a native Android APK and is not published on Google Play.
- It does not scan eBay or Facebook Marketplace automatically.
- It does not connect to live bank-switch, cashback, scrap-metal or crypto feeds.
- Data is stored in the current browser on the current device. It is not cloud-synced.
- Use current official offer terms and verified market prices before spending money.

## Test locally
Open `index.html` in a browser. For installable PWA behavior, host the files on an HTTPS static host. The service worker requires HTTPS or localhost.

## Next build stages
1. Test the prototype and refine the screens.
2. Add secure cloud persistence/authentication.
3. Add approved APIs and server-side handling for secrets.
4. Wrap/rebuild as a native Android app and complete Google Play testing/release.
