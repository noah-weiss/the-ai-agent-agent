# Domain: theaiagentagent.com

Registered: 2026-07-15  
Registrar: GoDaddy  
Expiry: 2027-07-15  
Privacy: Domains By Proxy  
Nameservers (current): ns25/ns26.domaincontrol.com

## Current live state (as of registration day)

GoDaddy Website Builder parking page: “Launching Soon.”
A records: 76.223.105.230, 13.248.243.5 (GoDaddy DPS)

## Target hosting

GitHub Pages from this repo’s `site/` directory.
Custom domain: **theaiagentagent.com** (+ www)

## GoDaddy DNS to set after Pages is ready

Remove Website Builder / parking A records. Replace with:

### Apex `@`

| Type | Name | Value | TTL |
|------|------|-------|-----|
| A | @ | 185.199.108.153 | 600 |
| A | @ | 185.199.109.153 | 600 |
| A | @ | 185.199.110.153 | 600 |
| A | @ | 185.199.111.153 | 600 |

### www

| Type | Name | Value | TTL |
|------|------|-------|-----|
| CNAME | www | noah-weiss.github.io | 600 |

### Optional HTTPS

GitHub Pages will issue HTTPS after DNS verifies. Enable “Enforce HTTPS” in repo Pages settings once available.

## Email (later)

Do not invent a mailbox. When ready:
- Google Workspace or Fastmail on the domain, or
- Forwarding alias in GoDaddy to personal inbox

Suggested: `hello@theaiagentagent.com` → Noah’s real inbox.

## Do not

- Leave the GoDaddy builder “Launching Soon” page as the public face once our site deploys
- Point nameservers away from GoDaddy unless we intentionally move DNS to Cloudflare
