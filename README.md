# chernobyl2-web

Static landing page for [chernobyl2.com](https://chernobyl2.com) (see root `CNAME`).

**GitHub Pages:** Repository **Settings** → **Pages** → **Build and deployment** → **Source: Deploy from a branch** → branch `main` and folder **/** (root). After the first deploy, **Custom domain** → `chernobyl2.com`, enable **Enforce HTTPS** once DNS is verified.

**DNS (registrar or DNS host):** Add an `A` record to GitHub’s [Pages IP addresses](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain), or a `CNAME` from `www` to `YOUR_USERNAME.github.io` if you use a `www` subdomain.
