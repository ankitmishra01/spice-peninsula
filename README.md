# The Spice Peninsula

A premium, single-page static website for **The Spice Peninsula**, an Indian-Cape Town fusion restaurant at the V&A Waterfront.

## Files

- `index.html` - page structure, SEO metadata, navigation, content, and small interaction script.
- `styles.css` - mobile-first responsive styling, brand palette, menu grid, sticky header, and scroll-reveal animations.

## Run Locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 3000
```

Then visit `http://localhost:3000`.

## Deploy to Vercel via GitHub

1. Create a new GitHub repository.
2. Push this folder to GitHub:

```bash
git remote add origin https://github.com/YOUR-USERNAME/spice-peninsula.git
git branch -M main
git push -u origin main
```

3. Sign in to [Vercel](https://vercel.com).
4. Select **Add New Project**.
5. Import the GitHub repository.
6. Keep the framework preset as **Other** or **Static**.
7. Leave the build command blank and set the output directory to `.` if prompted.
8. Click **Deploy**.

Vercel will publish the static site and provide a production URL.
