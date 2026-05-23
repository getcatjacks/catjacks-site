CATJACKS Decap CMS + Netlify Setup

Files added:
- /admin/index.html
- /admin/config.yml
- /data/gallery.json
- /assets/gallery/
- netlify.toml

Netlify steps:
1. Upload/deploy this full folder to Netlify, or push it to the GitHub repo connected to Netlify.
2. In Netlify: Site configuration > Identity > Enable Identity.
3. Set Registration to Invite only.
4. Invite your own email as a user.
5. Enable Git Gateway.
6. Visit https://getcatjacks.com/admin and log in.
7. Go to CATJACKS Gallery > Website Gallery Photos > Photos > Add item.
8. Upload a photo from your phone, add caption/category, then Publish.

Important:
- Decap CMS works best when the site is connected to a GitHub repo.
- New photos are stored in /assets/gallery and gallery data is stored in /data/gallery.json.
- The public gallery on the homepage reads /data/gallery.json automatically.
