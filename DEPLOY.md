# How to Deploy to Vercel (Free)

## Quick Setup (5 minutes)

### 1. Sign up for Vercel
- Go to https://vercel.com/signup
- Sign in with your **GitHub account** (easiest option)

### 2. Import the Repo
- Click **"Add New..."** → **"Project"**
- Find `stephenlthorn/app-legal` in the list
- Click **"Import"**

### 3. Deploy
- Framework Preset: **Other** (it's just HTML)
- Root Directory: `./` (leave default)
- Build Command: (leave empty)
- Output Directory: (leave empty)
- Click **"Deploy"**

### 4. Done!
Your site will be live at:
- **https://app-legal.vercel.app** (or similar)
- You can add a custom domain later (e.g., `legal.yourname.com`)

## Custom Domain (Optional)

### Free Option: Use a subdomain
- Buy a domain on Namecheap/Google Domains (e.g., `stephenthorn.com`)
- In Vercel: Settings → Domains → Add `legal.stephenthorn.com`
- Add DNS records as instructed

### No Domain Needed
- The `.vercel.app` URL works perfectly for App Store submission
- Apple accepts Vercel URLs

## URLs for App Store Connect

Once deployed, use these URLs:

**FlowCast Finance:**
- Privacy Policy: `https://app-legal.vercel.app/flowcast/privacy`
- Terms of Service: `https://app-legal.vercel.app/flowcast/terms`

(Replace `app-legal.vercel.app` with your actual Vercel URL)

## Adding New Apps

To add ADHD Call Reminder (or any future app):

1. Create folder: `adhd-call-reminder/`
2. Add `privacy.html` and `terms.html` (copy FlowCast structure)
3. Update `index.html` (uncomment the ADHD section)
4. Commit and push — Vercel auto-deploys!

```bash
cd /Users/stephenthorn/.openclaw/workspace/app-legal-site
mkdir adhd-call-reminder
# ... add files ...
git add -A
git commit -m "Add ADHD Call Reminder legal docs"
git push
```

Vercel will automatically rebuild in ~30 seconds.

## Cost

**Vercel Free Tier:**
- ✅ Unlimited static sites
- ✅ Custom domains
- ✅ Auto SSL (HTTPS)
- ✅ 100 GB bandwidth/month
- ✅ Auto-deploy from GitHub

**Perfect for legal docs** — you'll never exceed free tier limits.

---

Questions? Contact stephenlthorn@gmail.com
