# Mtakatifu Tips

Minimal static site to allow immediate deployment on Vercel.

How to deploy

- Using the Vercel Dashboard:
  1. Go to https://vercel.com and sign in with your GitHub account.
  2. Click "New Project" → "Import Git Repository" and select this repository.
  3. Use the default settings (root directory `/`) and click "Deploy".

- Using the Vercel CLI:
  1. Install: `npm i -g vercel`
  2. From this repository directory run: `vercel --prod`

Notes

- The repository now contains `index.html`. After deployment Vercel will provide a production URL.
- If you want a custom domain, add it in the Vercel project settings and follow the DNS instructions.
