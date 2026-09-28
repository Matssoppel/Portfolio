# Mats Ugland portfolio

A static website: seven HTML pages and an `img/` folder. It needs no build step and no server code.

## Publish on GitHub Pages (no Git needed)

1. Sign in at github.com and click **New repository**.
2. Name it `<your-username>.github.io` (for example `matsugland.github.io`), set it to **Public**, and click **Create repository**.
3. On the empty repository page, click **uploading an existing file**.
4. Open this folder on your computer, select everything inside it (the HTML files, the `img` folder and `.nojekyll`), and drag it into the browser window.
   - On a Mac, press Cmd+Shift+. in Finder to show the hidden `.nojekyll` file. It's optional, but it makes publishing faster.
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then branch `main` and folder `/ (root)`, and click **Save**.
7. After a minute or two, the site is live at `https://<your-username>.github.io`.

## Updating the site later

In the repository, click a file, then the pencil icon to edit it. Or use **Add file → Upload files** to replace files, and commit.

## Custom domain (optional)

Buy a domain (for example from domeneshop.no), then add it under **Settings → Pages → Custom domain** and follow GitHub's instructions for the DNS records.

## Files

| File | Page |
|---|---|
| index.html | Home |
| politiet-i-lomma.html | Politiet i lomma |
| snakk-til-meg.html | "Snakk til meg" |
| digitalisering-av-byggeplass.html | Prosjekthub |
| workshops.html | Campus workshop |
| pultlampe.html | Ampær |
| cv.html | CV |
| img/ | All images, named after the page they belong to |
