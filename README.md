MAVILIVE BODYCAM OVERLAY

FILES
- index.html = creator page
- overlay.html = transparent OBS overlay

IMPORTANT
For a real OBS Browser Source, the overlay must be hosted online with HTTPS.
Upload both HTML files to the same web hosting folder.

USAGE
1. Open index.html.
2. Enter Player Name.
3. Department is optional. Empty = CIVILIAN.
4. Click CREATE OVERLAY.
5. Copy the generated URL.
6. In OBS: Sources > Browser > paste the URL.
7. Set your desired width/height.

NOTE
This demo stores overlay data in browser localStorage. For production use across different devices/browsers, replace this with a small backend/database and unique public overlay records.
