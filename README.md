# Sacred Frame Media — Website

Official website for Sacred Frame Media, a spiritual retreat photography company.

## Project Structure

```
sacredframe-media/
├── index.html          ← Main website file
├── images/             ← All your photos go here
│   ├── hero.jpg        ← Hero section (best portrait shot)
│   ├── gallery-1.jpg   ← Gallery frame 1 (wide ceremony shot)
│   ├── gallery-2.jpg   ← Gallery frame 2 (teacher training group)
│   ├── gallery-3.jpg   ← Gallery frame 3 (close-up emotion)
│   ├── gallery-4.jpg   ← Gallery frame 4 (golden hour group)
│   └── gallery-5.jpg   ← Gallery frame 5 (quiet candid moment)
├── netlify.toml        ← Netlify configuration
└── README.md           ← This file
```

## How to Add Your Photos

1. Rename your Egypt photos to match the filenames above
2. Compress each photo to under 500KB using [squoosh.app](https://squoosh.app)
3. Drop them into the `/images` folder
4. Push to GitHub — Netlify auto-deploys in seconds

## Photo Guidelines

| Slot | Orientation | What works best |
|------|-------------|-----------------|
| hero.jpg | Portrait | Single powerful moment, face or emotion |
| gallery-1.jpg | Landscape | Wide ceremony or group shot |
| gallery-2.jpg | Landscape | Teacher training, people together |
| gallery-3.jpg | Any | Close-up, eyes closed, tears, hands |
| gallery-4.jpg | Landscape | Golden hour, Egypt backdrop visible |
| gallery-5.jpg | Any | Quiet candid, in-between moment |

## Deploying to Netlify

1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) → Add new site → Import from Git
3. Select this repository
4. Build settings are auto-detected via `netlify.toml`
5. Click Deploy — your site is live!

## Updating the Site

- Edit `index.html` to change text, copy, or layout
- Replace photos in `/images` folder
- Commit and push — Netlify deploys automatically

## Contact

hello@sacredframemedia.com
