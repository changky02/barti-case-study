# How to Host Your HTML Files

## Option 1: GitHub Pages (Recommended - Free & Easy)

### Steps:
1. **Create a GitHub repository:**
   - Go to https://github.com/new
   - Name it: `barti-case-study` (or any name)
   - Make it public
   - Click "Create repository"

2. **Upload your files:**
   - Click "uploading an existing file"
   - Drag and drop these files:
     - `framework-overview.html`
     - `roadmap-prioritization-dark.html`
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 1-2 minutes

4. **Your files are now live at:**
   ```
   https://YOUR-USERNAME.github.io/barti-case-study/framework-overview.html
   https://YOUR-USERNAME.github.io/barti-case-study/roadmap-prioritization-dark.html
   ```

5. **Use in Gamma:**
   - Add an iframe/embed block
   - Paste the GitHub Pages URL
   - Done!

---

## Option 2: Netlify Drop (Super Easy, Free)

### Steps:
1. Go to https://app.netlify.com/drop
2. Create a folder on your computer with the HTML files
3. Drag the folder to Netlify Drop
4. Get instant URL like: `https://random-name-12345.netlify.app/framework-overview.html`

**Pros:** Instant, no account needed
**Cons:** Random URL (can upgrade to custom domain)

---

## Option 3: Cloudflare Pages (Free)

### Steps:
1. Sign up at https://pages.cloudflare.com/
2. Create new project
3. Upload your HTML files
4. Get URL like: `https://barti-case-study.pages.dev/framework-overview.html`

**Pros:** Fast CDN, professional
**Cons:** Requires account setup

---

## Option 4: Vercel (Free)

### Steps:
1. Sign up at https://vercel.com/
2. Install Vercel CLI: `npm install -g vercel`
3. In your terminal:
   ```bash
   cd /Users/kevinchang/Barti-project/Insurance-Eligibility-Case-Study/deck-restructured
   vercel
   ```
4. Follow prompts
5. Get URL like: `https://barti-case-study.vercel.app/framework-overview.html`

---

## Quick Comparison:

| Service | Setup Time | URL Quality | Best For |
|---------|-----------|-------------|----------|
| **GitHub Pages** | 5 minutes | Good | Version control + hosting |
| **Netlify Drop** | 30 seconds | Random | Quick demo |
| **Cloudflare** | 3 minutes | Professional | Production use |
| **Vercel** | 2 minutes (CLI) | Professional | Developers |

---

## Recommendation:

**For this case study:** Use **GitHub Pages**
- Free forever
- Easy to update files later
- Professional URLs
- No expiration

---

## Need Help?

I can help you set up any of these options. Just let me know which one you prefer!
