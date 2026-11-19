# Dash BR Selector

Android app: pick a drive and its size (kW) to see max output current, braking resistor (BR)
for ≤7 floors / >7 floors, notes and the wiring diagram.

- Data: `app/src/main/assets/www/data.js` (generated from the Excel sheet)
- Wiring pictures: `app/src/main/assets/www/img/`
- Drive photos: put them in `app/src/main/assets/www/img/drives/` named like `ls-s100l-2.png`,
  `dlift-n1000g1.png` (lower-case drive name, spaces/dots → `-`). Drives without a photo show a name tile.

Every push to `main` builds the APK on GitHub Actions and attaches it to the **latest** release.
