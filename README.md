# iglesiacda.org: static landing page

A one-page bilingual (ES/EN) holding page for Iglesia Casa de Adoración, served by GitHub
Pages until the domain expires (Hover, **2027-05-22**). The care plan has ended; this
replaces the WP Engine site. No giving details on purpose (spam).

- `index.html`: the page. Plain HTML, inline CSS, no images or scripts.
- `404.html`: a copy of `index.html`, so old WordPress URLs (`/giving/`, `/es/casa/`…) show
  the info instead of an error. **Re-copy it after any edit to `index.html`.**
- `CNAME`: custom domain iglesiacda.org (set 2026-10-12, before the DNS cutover).

## Status

- [x] Page built and checked locally (desktop + phone)
- [x] GitHub repo created, Pages on (main, `/`): https://tomatillodesign.github.io/iglesiacda/
- [x] Domain verified in GitHub account settings (TXT at Hover)
- [ ] Hover DNS: apex A → 185.199.108.153 / .109.153 / .110.153 / .111.153
      (replacing WPE 141.193.213.10/.11); `www` CNAME → `tomatillodesign.github.io`.
      **Leave MX alone** (mx.hover.com.cust.hostedemail.com).
- [x] Set custom domain `iglesiacda.org` (adds `CNAME`)
- [ ] Enforce HTTPS once the cert issues; check apex + www
- [ ] Final WPE backup for the client, then remove domain from WPE and retire the install
- [ ] Before 2027-05-22: offer the client a domain transfer, or turn off auto-renew
