# Aditya Aggrawal: Portfolio

Personal portfolio website for Aditya Aggrawal, full-stack and AI developer.

It's a static site: one `index.html` plus images, with no build step, framework or dependencies to install.

## What's inside

```
index.html      the whole site (HTML, CSS and JavaScript in one file)
aditya.jpg      profile photo
img/            project photos, Site Studio photos and company logos
README.md       this file
```

## Put it on GitHub

1. Create a new repository on GitHub, for example `portfolio`.
2. Upload everything in this folder: drag the files onto the repository page and click **Commit changes**. Or use the terminal:

   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/Aditya-OO1/portfolio.git
   git push -u origin main
   ```

   Keep `index.html` at the top level of the repository, not inside a subfolder.

## Make it live on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
2. Click **Add New → Project** and import the `portfolio` repository.
3. Leave **Framework Preset** as **Other**, and leave the build and output settings empty.
4. Click **Deploy**. The site is live in under a minute at `https://<project-name>.vercel.app`.
5. Optional: add your own domain under **Project → Settings → Domains**.

Every time you push a change to GitHub, Vercel redeploys automatically.

## After it's live

- **Link previews:** in `index.html`, change `<meta property="og:image" content="aditya.jpg">` to the full address, for example `https://your-site.vercel.app/aditya.jpg`. WhatsApp, LinkedIn and similar apps need the full address to show your photo when you share the link.
- **Internet connection:** fonts load from Google Fonts. Everything else is included in this folder.

## Photo credits

The project and Site Studio photos come from [Unsplash](https://unsplash.com) and are free to use under the [Unsplash License](https://unsplash.com/license). Credit isn't required. Company logos belong to their owners.
