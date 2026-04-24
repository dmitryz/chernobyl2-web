# chernobyl2-web

Static landing page. Default URL: `https://dmitryz.github.io/chernobyl2-web/`. Custom domain `chernobyl2.com` only after DNS points to GitHub (see below).

**GitHub Pages:** **Settings** → **Pages** → **Deploy from a branch** → `main` and **`/ (root)`**. To use a custom domain only when DNS is ready: set **Custom domain** and add the A/AAAA (or CNAME) records; then enable **Enforce HTTPS**.

**DNS (registrar or DNS host):** Add an `A` record to GitHub’s [Pages IP addresses](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain), or a `CNAME` from `www` to `YOUR_USERNAME.github.io` if you use a `www` subdomain.
