# Chen Liang Faculty Site

This folder is a static HTML website tailored for business school faculty applications.

Files:

- `index.html` - the webpage
- `styles.css` - styling
- `portrait.jpg` - bundled headshot
- `Chen_Liang_CV.pdf` - downloadable CV

To preview locally:

```bash
cd "/Users/chenliang/Desktop/apps/job market/faculty-site"
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

To make it accessible to others:

1. Upload the entire `faculty-site` folder to GitHub Pages, Netlify, Vercel, or any static host.
2. Make sure `index.html` stays at the site root.
3. Keep `styles.css`, `portrait.jpg`, and `Chen_Liang_CV.pdf` in the same folder as `index.html`.

Fastest no-code option:

1. Go to Netlify Drop.
2. Drag the whole `faculty-site` folder into the browser.
3. Netlify will give you a public URL you can share immediately.
