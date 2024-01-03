Deploy it on cloudflare workers.

https://developers.cloudflare.com/workers/get-started/guide/#4-deploy-your-project

# Guide
 - go to your cloudflare dashbard.
 - then go to workers section. ![image](https://github.com/animemandir/ts_api/assets/78192713/17db5bbf-b2e2-47cd-bcfa-a6b74b727ee1)
 - Install Wrangler `npm install -g wrangler`.
 - Authenticate Wrangler with your Cloudflare account.
 To enable Wrangler to deploy your scripts to Cloudflare, you'll need to authenticate by logging in to your Cloudflare account.
 - `wrangler login`
When wrangler automatically opens your browser to display Cloudflare’s consent screen, click the Allow button. This will send an API Token to Wrangler.
Initialise a new project from this Worker

  `wangler init --from-dash your-worker-name`

Publish your Wrangler project

Deploy your project to Cloudflare’s global network:

`wrangler publish`

That’s it! 🎉
