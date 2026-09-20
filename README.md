### Hi! I'm Jeremiah
*Software Engineer*

---

### Let's connect..

> Twitter: [@jerrylusato](https://twitter.com/jerrylusato)
>
> Email Address: [jeremiahlusato@gmail.com](mailto:jeremiahlusato@gmail.com)
> 
> WhatsApp: [0710557678](https://wa.me/255710557678)

## Deployment

Cloudflare Workers Builds automatically deploys every push to `main`, including
merge commits, to the `my-website` Worker serving
[jerrylusato.com](https://jerrylusato.com/). Non-production branches do not
deploy to this Worker.

The Worker serves only `index.html`. The `.assetsignore` allowlist prevents Git
metadata, documentation, and other repository files from being published as
static assets. After deployment, verify that `/` returns the homepage and that
`/.git/HEAD` returns `404`.
