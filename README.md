# My ADHD Assistant — Website

Static site for myadhdassistant.com. Four pages required for Twilio A2P 10DLC registration.

## Files

| File | URL | Purpose |
|---|---|---|
| `index.html` | / | About / landing page |
| `privacy.html` | /privacy.html | Privacy Policy |
| `terms.html` | /terms.html | Terms of Service |
| `opt-out.html` | /opt-out.html | Help & Opt-Out |

## Deployment (GitHub Pages)

1. Create a new GitHub repo: `myadhdassistant-site` (can be private)
2. Push these files to the `main` branch
3. In repo Settings → Pages → Source: select `main` branch, root folder
4. Add custom domain: `myadhdassistant.com`
5. In your DNS (M365/registrar), add a CNAME record:
   - Name: `www`
   - Value: `[yourusername].github.io`
   - For apex domain, add four A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
6. Check "Enforce HTTPS" in GitHub Pages settings once DNS propagates

## Twilio verification URLs to submit

- Opt-in / About: https://myadhdassistant.com
- Privacy Policy: https://myadhdassistant.com/privacy.html
- Terms of Service: https://myadhdassistant.com/terms.html
- Opt-Out: https://myadhdassistant.com/opt-out.html
