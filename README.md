# Keepgate - Landing Page

Landing page for Keepgate - the "never forget important dates" app.

## Setup

### 1. Formspree (Email Capture)
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form
3. Copy the form ID (looks like `xyzabcde`)
4. Replace `YOUR_FORM_ID` in `index.html` with your actual form ID

### 2. Deploy Options

**Option A: Vercel (Recommended)**
```bash
npm i -g vercel
cd projects/keepgate
vercel
```

**Option B: Netlify**
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop this folder to deploy

**Option C: GitHub Pages**
1. Push to a GitHub repo
2. Enable Pages in repo settings

### 3. Connect Domain
After deploying, point `keepgate.com` DNS to your hosting provider:
- Vercel: Add domain in project settings
- Netlify: Add custom domain in site settings

## Files
- `index.html` - Main landing page (single file, no build needed)

## Ad Testing
Once live, test with:
- Google Ads: $50-100 budget, target "birthday reminder app" keywords
- Facebook/Instagram: Interest targeting for productivity/organization

Track signups in Formspree dashboard.
