# Solva — STEM Homework Solver

A homework solver for Math, Physics, Chemistry, Biology, and Statistics — with a custom keyboard, draw mode, and photo snap powered by Claude AI.

## Deploy to Vercel (free)

### 1. Push to GitHub
- Create a new repo on github.com
- Upload all these files keeping the same folder structure:
  ```
  solva/
  ├── api/
  │   └── proxy.js
  ├── public/
  │   └── index.html
  ├── vercel.json
  └── package.json
  ```

### 2. Connect to Vercel
- Go to [vercel.com](https://vercel.com) and sign in with GitHub
- Click **Add New Project** → import your `solva` repo
- Click **Deploy** (no build settings needed)

### 3. Add your API key
- In Vercel dashboard → your project → **Settings** → **Environment Variables**
- Add: `ANTHROPIC_API_KEY` = your key from [console.anthropic.com](https://console.anthropic.com)
- Go to **Deployments** → click the 3 dots on your latest deploy → **Redeploy**

Your app will be live at `https://solva-yourname.vercel.app` 🎉

## Get an Anthropic API Key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in
3. Go to **API Keys** → **Create Key**
4. Copy it and paste into Vercel as shown above
