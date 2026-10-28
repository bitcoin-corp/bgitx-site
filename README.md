# bGitX.com

Marketing site for **bGitX**, your code on b. By The Bitcoin Corporation Ltd. Static HTML, same house pattern as bsignx-site.

Loop: connect GitHub → mint a private, encrypted repo snapshot → open a bChatX room → invite collaborators → agree terms in bSignX → Kintsugi opens pull requests; nothing merges without the owner's OK.

Sources: `bitcoin-corp/docs/BX-SERVICE-MAP.md` (bGitX rows) and `bitcoin-corp/docs/KINTSUGI-ORDERS.md`.

## Develop

```
pnpm install
pnpm build   # html-validate + local asset check
```

OG image source: `media-src/og-bgitx-v1.html` (render 1200x630 with headless Chrome). Deploys from GitHub via Vercel (`vercel.json`: static, output `.`).
