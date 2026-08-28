# EagleEye Labs LLC

Company site for EagleEye Labs LLC.

Repo: [eagleeyegolfapp/EagleEye-Labs-LLC](https://github.com/eagleeyegolfapp/EagleEye-Labs-LLC)

GitHub Pages is already on for this repo. Custom domain currently set in Pages settings: `eagleeyelabs.org`.

## Point eagleeyelabsllc.com (Squarespace)

You can either:

**A. Forward the new domain to the existing Pages domain**  
In Squarespace, set `eagleeyelabsllc.com` to forward to `https://eagleeyelabs.org`.

**B. Make eagleeyelabsllc.com the Pages custom domain**  
1. GitHub repo → **Settings → Pages → Custom domain** = `eagleeyelabsllc.com`
2. Add a `CNAME` file in the repo containing `eagleeyelabsllc.com`
3. Squarespace DNS:

| Type | Host | Data |
|------|------|------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `eagleeyegolfapp.github.io` |

Then enable **Enforce HTTPS** after DNS propagates.

## Local preview

```bash
python3 -m http.server 8080 --directory .
```
