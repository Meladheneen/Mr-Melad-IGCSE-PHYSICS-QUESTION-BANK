# Mr. Milad Physics Lab — GitHub Pages Frontend

This folder is the **public/static frontend only**. Upload this folder contents to a GitHub repository.

## One required edit
Open `index.html` and change:

```js
let API_BASE = 'https://YOUR-WORKER.your-subdomain.workers.dev';
```

to your private Cloudflare Worker URL.

**Never upload the `PRIVATE_BACKEND` folder to a public GitHub repository.** GitHub Pages supports static HTML/CSS/JS but not server-side PHP.
