# 1508 17th Street — Property Microsite

Leasing microsite for 1508 17th Street, Santa Monica, CA 90404.  
Built for Lee & Associates West LA.

## File Structure

```
1508-17th-street/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    ├── LWLA_logo_Black-2.png
    ├── LWLA_Front_Lights_On_Dusk.jpg
    ├── LWLA_Front_Lights_on_Dusk_Vertical.jpg
    ├── LWLA_Front_View_with_Street.jpg
    ├── LWLA_Front_Daytime.jpg
    ├── LWLA_Patio.jpg
    ├── LWLA_Parking.jpg
    ├── LWLA_Night.jpg
    ├── LWLA_Front_Sidewalk.jpg
    └── Lee_West_at_Night_copy.jpg
```

## Setup

1. Place all images in the `/images/` folder (filenames must match exactly).
2. Open `index.html` in a browser to preview locally.
3. Deploy via Cloudflare Pages (see below).

## Deploying to Cloudflare Pages

1. Push this folder to a GitHub repository.
2. Log into Cloudflare → **Pages** → **Create a project**.
3. Connect your GitHub account and select the repository.
4. Set:
   - **Framework preset**: None
   - **Build command**: *(leave blank)*
   - **Build output directory**: `/` (root)
5. Click **Save and Deploy**.

Your site will be live at `https://<your-project>.pages.dev` within ~60 seconds.

## Updating Content

- Edit property details in `index.html`.
- Swap images in the `/images/` folder (keep filenames identical).
- Push changes to GitHub — Cloudflare Pages redeploys automatically.
