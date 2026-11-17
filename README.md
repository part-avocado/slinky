# Slinky
> [!Note]
> OwO wots this? This is basically a remake of the heavily vibe-glopped but pretty good [botnick/shortlink](https://github.com/botnick/shortlink) URL shortener for Cloudflare Workers. 

## Featureset:
- [] Deployable to Cloudflare Workers!
- [] Uses KV databases to store values quickly and efficiently
- [] A visually appealing and useful dashboard powered by Clerk (auth)
- [] CF Turnstile bot prevention
- [] cool load animation
- [] expiry
- [] pause
- [] per-country routing
- [] password-protected links
- [] UTM builder
- [] bulk importa
- [] send visitors from specific countries (ISO-3166) to different URLs; matched at the edge from request.cf.country, ahead of the per-OS targets. No extra service, no cost. (from https://github.com/botnick/shortlink)
- [] Cloudflare Analytics