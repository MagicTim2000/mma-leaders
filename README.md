# MMA Leaders launcher

A one-page launcher so leaders get a home-screen button with our logo, called "MMA Leaders".
Google Apps Script pages can't set their own home-screen icon, so this page carries the icon and name
and forwards straight on to the leader view (which still needs the leader PIN).

- Live at https://leaders.magicacademy.com.au (GitHub Pages, public repo `MagicTim2000/mma-leaders`).
- First visit from the shared link: shows the logo, an "Open the leader view" button and how to add it to the home screen.
- Opened from the home-screen button (`?go=1`): jumps straight to the leader view.
- Holds no family or child details. Only the logo, the name and the leader-view link.
- If the leader-view link ever changes, update `APP` in `index.html` and push to the public repo too.
- Icons are drawn from `../holiday-checkin/src/assets/logo.png` on the app's blue (#3A6BAA).
