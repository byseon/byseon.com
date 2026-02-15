# byseon.com

Personal homepage for SEON. Static HTML + CSS, hosted on GitHub Pages.

## Deploy

### GitHub Pages

1. Push this repo to `github.com/byseon/byseon.github.io` (or any repo with Pages enabled).
2. Go to **Settings > Pages**.
3. Set source to **Deploy from a branch**, select `main` / `root`.
4. The `CNAME` file tells GitHub to serve from `byseon.com`.

### Cloudflare DNS

1. Add your domain to Cloudflare.
2. Set nameservers at your registrar to Cloudflare's.
3. Add DNS records:

| Type  | Name | Content            |
|-------|----- |--------------------|
| A     | @    | 185.199.108.153    |
| A     | @    | 185.199.109.153    |
| A     | @    | 185.199.110.153    |
| A     | @    | 185.199.111.153    |
| CNAME | www  | byseon.github.io   |

4. In Cloudflare **SSL/TLS**, set mode to **Full**.
5. Enable **Always Use HTTPS** under **Edge Certificates**.
6. In GitHub repo **Settings > Pages > Custom domain**, enter `byseon.com` and save.
7. Wait for GitHub to provision the SSL certificate (should show a green check).

### Verify

```
curl -I https://byseon.com
```

Should return `200` with proper headers.

## Structure

```
index.html    — page
styles.css    — styles
favicon.svg   — favicon
CNAME         — custom domain
robots.txt    — crawl rules
sitemap.xml   — sitemap
```

## License

Content and design by SEON.
