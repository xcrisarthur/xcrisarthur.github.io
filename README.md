# xcrisarthur.github.io

Portfolio frontend — di-host di [GitHub Pages](https://xcrisarthur.github.io/).

Konten dinamis (CMS, foto, admin) dilayani oleh API di VPS:
`https://103-144-126-90.sslip.io/portfolio-api`

Sumber edit: repo [arthur-portfolio](https://github.com/xcrisarthur/arthur-portfolio) / `homelabz/portfolio-web`.

Deploy ulang setelah perubahan:

```bash
~/homelabz/scripts/sync-github-pages.sh
cd ~/xcrisarthur.github.io && git add -A && git commit -m "sync: portfolio web" && git push
```
