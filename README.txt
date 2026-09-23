MAVILIVE Bodycam - FIXED VERSION

Files:
- index.html = generator/setup page
- overlay.html = OBS transparent overlay

Important fix:
The OBS URL contains Player Name, Department and start time directly in the URL.
It does NOT use localStorage and it does NOT expire.

Example:
https://YOUR-DOMAIN/overlay.html?player=Mavi&department=POLICE&start=...

Cloudflare:
Replace the existing index.html and overlay.html in the connected GitHub repository.
If Cloudflare Workers Builds is connected to GitHub, push/commit the changes and Cloudflare will create a new deployment.
Otherwise use the Cloudflare Worker dashboard -> Edit code and replace the corresponding files/assets, then Deploy.

Branding update:
Visible branding is now "BODYCAM BY MAVILIVE" on the setup page and OBS overlay.
The fixed self-contained OBS URL system is unchanged.

Live Preview branding: BODYCAM BY MAVILIVE.
