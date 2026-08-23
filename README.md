# Inside Edge Studios website

Static website for `www.insideedge-studios.com`, designed for GitHub Pages.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publishing

1. Create a GitHub repository for this website.
2. Push these files to its `main` branch.
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, and `/ (root)`.
4. Set the custom domain to `www.insideedge-studios.com` and enable HTTPS.

## Adding another app

Copy the `insideedgeride` directory as a starting point, rename it with a short lowercase URL slug, and update its content and metadata. Add the app to the home page and `sitemap.xml`.

## Before launch

- Confirm `insideedgedevstudios@gmail.com` is active and monitored.
- Recheck the privacy policy against the shipping app and App Store privacy answers.
- Replace or add the App Store button once the public App Store URL is known.
