ONE‑PAGE TOOLS & GAMES — STARTER

How to use:
1) Edit index.html to rename your site and add more cards.
2) Add your AdSense code (after approval) where you see "Ad placeholder".
3) Deploy with one of these:
   - Vercel: drag this folder into a new project
   - Netlify: drag & drop the folder into Netlify dashboard
   - GitHub Pages: push to a repo and enable Pages (branch: main, folder: /root)

Add more tools/games:
- Create a new HTML file under /utils or /games/<name>/index.html
- Link it from index.html

SEO:
- Update <title> and <meta name="description">.
- Replace your-domain in robots.txt and sitemap.xml with your real domain.

Unity WebGL:
- Build → WebGL → copy the Build folder into /games/<yourgame>/ and add an index.html that loads the build.
