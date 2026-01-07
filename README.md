# html
# CACPT Connect

CACPT Connect is a lightweight interactive hub for church life — an HTML/CSS/JS single-page UI to surface livestreams, announcements, Zoom meeting info and a simple calendar. Settings persist in browser localStorage.

## Features
- Responsive dashboard with live stream player (YouTube / Vimeo embed parsing)
- Admin settings to configure stream URL, announcements and Zoom details
- Simple event calendar UI and day sidebar
- English / Spanish translations
- Local persistence via localStorage (key: `cacpt_connect_v3`)

## Preview locally
Option A — open file:
1. Open `cacpt.html` in your browser.

Option B — serve via a simple server (recommended):
```bash
cd /home/codethug/Documents/html
python3 -m http.server 8000
# then open http://localhost:8000/cacpt.html
```

## Configuration
- Admin → fill in Live Stream URL, Announcement, Zoom Link/ID/Pass → Save.
- Data stored in localStorage under `cacpt_connect_v3`.
- To reset settings: open browser DevTools → Application → Local Storage → delete `cacpt_connect_v3`.

## Deployment
- Create a GitHub repo and push the folder, or use GitHub Pages to host the static files.
Example:
```bash
cd /home/codethug/Documents/html
git init
git add -A
git commit -m "Add CACPT Connect"
git branch -M main
# add remote and push (replace placeholders)
git remote add origin git@github.com:YOUR_USER/REPO_NAME.git
git push -u origin main
```

## Notes & TODO
- Chat is demo-only (disabled).
- Consider server-backed storage for multi-admin support and real events.
- Improve accessibility and keyboard navigation for the calendar and controls.

## License
MIT — see LICENSE for details.
```// filepath: /home/codethug/Documents/html/README.md

# CACPT Connect

CACPT Connect is a lightweight interactive hub for church life — an HTML/CSS/JS single-page UI to surface livestreams, announcements, Zoom meeting info and a simple calendar. Settings persist in browser localStorage.

## Features
- Responsive dashboard with live stream player (YouTube / Vimeo embed parsing)
- Admin settings to configure stream URL, announcements and Zoom details
- Simple event calendar UI and day sidebar
- English / Spanish translations
- Local persistence via localStorage (key: `cacpt_connect_v3`)

## Preview locally
Option A — open file:
1. Open `cacpt.html` in your browser.

Option B — serve via a simple server (recommended):
```bash
cd /home/codethug/Documents/html
python3 -m http.server 8000
# then open http://localhost:8000/cacpt.html
```

## Configuration
- Admin → fill in Live Stream URL, Announcement, Zoom Link/ID/Pass → Save.
- Data stored in localStorage under `cacpt_connect_v3`.
- To reset settings: open browser DevTools → Application → Local Storage → delete `cacpt_connect_v3`.

## Deployment
- Create a GitHub repo and push the folder, or use GitHub Pages to host the static files.
Example:
```bash
cd /home/codethug/Documents/html
git init
git add -A
git commit -m "Add CACPT Connect"
git branch -M main
# add remote and push (replace placeholders)
git remote add origin git@github.com:YOUR_USER/REPO_NAME.git
git push -u origin main
```

## Notes & TODO
- Chat is demo-only (disabled).
- Consider server-backed storage for multi-admin support and real events.
- Improve accessibility and keyboard navigation for the calendar and controls.

## License
MIT — see LICENSE for details.