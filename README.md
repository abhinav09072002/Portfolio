# Abhinav Verma — Portfolio

## How to Deploy on Netlify

### Option 1: Drag & Drop (Easiest — No GitHub needed)
1. Go to https://app.netlify.com
2. Sign up / log in (free)
3. On the dashboard, find the **"Add new site"** → **"Deploy manually"** section
4. Drag and drop this entire **`abhinav-portfolio`** folder onto the page
5. Done! Netlify gives you a live URL instantly (e.g. `https://random-name.netlify.app`)
6. To set a custom name: Site settings → General → Change site name

### Option 2: Deploy via GitHub (Recommended for auto-updates)
1. Create a new repo on https://github.com/new (e.g. `my-portfolio`)
2. Upload the files (index.html, resume.pdf) to the repo
3. Go to https://app.netlify.com → "Add new site" → "Import an existing project"
4. Connect GitHub → Select your repo
5. Build settings: leave blank (no build command needed for plain HTML)
6. Click **Deploy site**
7. Every time you push to GitHub, Netlify auto-redeploys!

### Custom Domain (Optional)
- In Netlify: Site settings → Domain management → Add custom domain
- Point your domain's DNS to Netlify's nameservers

### Notes
- `resume.pdf` must stay in the same folder as `index.html` for the download button to work
- The contact form is UI-only; to make it functional connect Netlify Forms or EmailJS
