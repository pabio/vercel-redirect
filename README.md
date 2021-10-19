# ➡️ Vercel Redirect

Often times, we have parked domains (like `mail.pabio.com`, with which we send emails) and we need an easy way to redirect them to `pabio.com` in case anyone visits. This repository does just that.

## ℹ️ How it works

- [`vercel.json`](./vercel.json) contains a wildcard rule to permanently redirect to `pabio.com`
- The Vercel project [pabio/vercel-redirect](https://vercel.com/pabio/vercel-redirect) (internal link) runs this configuration file
- We add all parked domains to this project (see [Custom domains](https://vercel.com/docs/concepts/projects/custom-domains) on Vercel)
- That's it, all of these domains now redirect to our site
