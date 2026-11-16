# Download It — website

Landing page for [Download It](https://github.com/arnabbagxd/Downloader), a free, native macOS downloader for video, images and PDFs.

It's a single static page: `index.html` plus `app-icon.png`. No build step.

## Run locally

```sh
python3 -m http.server 4321
```

Then open http://localhost:4321.

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For GitHub Pages: Settings → Pages → deploy from the `main` branch, root folder.

## Notes

- The download buttons link to the latest release asset: `releases/latest/download/DownloadIt-macos-universal.dmg`.
- The GitHub star count and version number load live from the GitHub API, with `v1.3.0` as the fallback.
- Smooth scrolling uses [Lenis](https://github.com/darkroomengineering/lenis) from jsDelivr. Animations and smooth scroll turn off for visitors with reduced motion enabled.
- Fonts: Geist, Geist Mono and Inter from Google Fonts.
- Icons: [Lucide](https://lucide.dev) (ISC). Site logos: [Simple Icons](https://simpleicons.org) (CC0); the names and logos belong to their owners.
