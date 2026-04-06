# Custom Domain Guide for GitHub Pages

When you're ready to replace `noeticsoul.github.io` with your own domain, use a **www subdomain** if possible. GitHub recommends `www` because it is the most stable option.

## Recommended setup
Example target:
- `www.yourdomain.com` -> your GitHub Pages site
- optional redirect from `yourdomain.com` -> `www.yourdomain.com`

## In GitHub
1. Open your repository
2. Go to **Settings > Pages**
3. Add your custom domain
4. Wait for GitHub to provision HTTPS
5. Turn on **Enforce HTTPS** when available

## In your domain registrar / DNS provider
### For a www subdomain
Create a **CNAME** record:
- Host: `www`
- Value: `noeticsoul.github.io`

### If you also want the apex domain
Create the appropriate **A**, **ALIAS**, or **ANAME** records based on your provider, then point the apex to GitHub Pages and let GitHub handle redirects.

## Important notes
- Verify your custom domain in GitHub for better security
- Avoid wildcard DNS records like `*.yourdomain.com`
- HTTPS can take a little while to become available after DNS is set up
