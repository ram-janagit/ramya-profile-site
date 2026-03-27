# Ramya — Profile site (Netlify-ready)

This is a lightweight, static profile site generated from your CV.

## Run locally (optional)

If you have Python:

```bash
cd profile-site
python3 -m http.server 5173
```

Then open `http://localhost:5173`.

## Deploy on Netlify (Free)

### Option A — Drag & drop (fastest)

1. Go to Netlify and log in.
2. Click **Add new site → Deploy manually**.
3. Drag the `profile-site/` folder into the upload area.
4. Wait for deploy → you’ll get a URL like `https://something.netlify.app`.
5. To change it: **Site settings → Site details → Change site name**.

### Option B — GitHub (best for updates)

1. Create a GitHub repo and push this `profile-site/` folder.
2. Netlify: **Add new site → Import from Git**.
3. Build command: *(leave empty)*
4. Publish directory: `.`

