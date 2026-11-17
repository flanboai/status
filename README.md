# status

Temporary maintenance page for flanboai.com while the main site is offline.

## Switch back to the real site (Vercel)
At Squarespace → flanboai.com → DNS → Custom records, restore:
- `A`     `@`   → `76.76.21.21`
- `CNAME` `www` → `cname.vercel-dns.com`
and delete the GitHub Pages records added for this page.
