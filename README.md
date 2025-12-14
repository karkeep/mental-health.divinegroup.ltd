# MindCare Landing Page

A beautiful, responsive landing page for the MindCare Mental Health App.

## Deploy to Vercel

### Option 1: Deploy from this folder

1. Go to [vercel.com](https://vercel.com)
2. Import this `landing` folder as a new project
3. Set the **Root Directory** to `landing`
4. Deploy!

### Option 2: Deploy via CLI

```bash
cd landing
npx vercel
```

### Option 3: Separate Repository

If you want to keep the landing page in a separate repo:

```bash
# Create new folder outside this project
mkdir ~/mindcare-landing
cp -r landing/* ~/mindcare-landing/
cd ~/mindcare-landing
git init
git add .
git commit -m "Initial landing page"
# Push to GitHub, then connect to Vercel
```

## Custom Domain

After deploying to Vercel:
1. Go to Project Settings → Domains
2. Add `www.mental-health.divinegroup.ltd`
3. Configure DNS at your domain registrar:
   - Add CNAME record pointing to `cname.vercel-dns.com`

## Local Development

```bash
npx serve .
```

Then open http://localhost:3000
