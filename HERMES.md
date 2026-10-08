# jupid-site — landing for Jupid (stub)
- Static single-page site: `index.html` (inline CSS/JS, Google Fonts Instrument Serif + Geist), `favicon.svg`, `CNAME` (jupid.bid), `404.html`.
- Hosting: GitHub Pages, repo `Aminatorex/jupid-site` (public), branch `main`, root. Push = deploy.
- DNS at Namecheap (BasicDNS): apex A → 185.199.108-111.153, `www` CNAME → aminatorex.github.io. Email forwarding MX records kept.
- Waitlist form is a stub (localStorage only, no backend). Content is placeholder — project not validated.
- QA: `chromium --headless=new --window-size=1440,6400 --screenshot=... file://$PWD/index.html`
