Flydigi Apex 5 GPV Skin (simple package)
========================================

Files included:
- skin.png                (the controller image)
- flydigi-apex5.css       (CSS referencing skin.png)
- README.txt              (this file)

How to get a usable link for GamePadViewer (GPV)
------------------------------------------------
Option A — GitHub (recommended)
1. Create a new GitHub repository (public).
2. Upload both skin.png and flydigi-apex5.css to the repo (in the root).
3. Go to the CSS file in GitHub, click "Raw". Copy the raw file URL.
   Example raw URL format:
   https://raw.githubusercontent.com/<username>/<repo>/main/flydigi-apex5.css
4. Paste that raw URL into GPV's "Custom CSS URL" field when creating a new GamePad.

Important: GitHub raw URLs can block images due to CORS. If the skin doesn't load, use jsDelivr:
- Convert the raw URL to a jsDelivr URL:
  https://cdn.jsdelivr.net/gh/<username>/<repo>@main/flydigi-apex5.css

Option B — GitHub Gist
1. Create a gist containing flydigi-apex5.css and upload skin.png as a file (Gist supports images).
2. Use the raw URL for the CSS file or host images elsewhere and reference the absolute URL.

Option C — Netlify / Vercel / any static host
1. Upload both files to any static host.
2. Use the absolute URL to the CSS file in GPV.

Using the CSS in GPV
--------------------
1. Open https://gamepadviewer.com
2. Click "Create GamePad"
3. For "GamePad skin" choose "Custom CSS URL"
4. Paste the final CSS URL (from GitHub/Gist/jsDelivr/Netlify)
5. Click "Create"

Notes & Next steps
------------------
- This package is a minimal working example (single background image).
- For perfect button highlights and exact mapping, I can:
  * generate a sliced-overlay PNG (separate transparent layers for each button)
  * write detailed CSS with absolute positions per button
  * upload everything and provide a direct working jsDelivr URL
If you want that, tell me and I will create the fully mapped skin and host it for you.