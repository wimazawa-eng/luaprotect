# LuaProtect – static site

Live URL: `https://your-username.github.io/luaprotect`

## Deploy in 10 s

| Host          | One-liner                                                                 |
|---------------|---------------------------------------------------------------------------|
| **GitHub Pages** | Push to `main` → enable Pages → done (already included `.github/workflows/pages.yml`) |
| **Netlify**      | `npx netlify deploy --prod --dir=.`                                      |
| **Vercel**       | `npx vercel --prod`                                                       |
| **Cloudflare Pages** | Upload zip or `npx wrangler pages deploy .`                         |
| **Surge.sh**     | `npx surge` (follow prompts)                                              |

All files are 100 % static—no build step.
