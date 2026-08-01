# Deployment Steps

1. **GitHub**: Create a public repo (e.g. `surya-portfolio`), push this folder to it.
2. **Netlify** (free): New site from Git → pick the repo → deploy (no build command needed, publish dir = root).
3. **Domain**: Site gets a free `yourname.netlify.app` subdomain automatically. Rename it under Site settings → Domain management → Options → Edit site name.
4. **Admin login (Decap CMS)**:
   - In Netlify: Site settings → Identity → Enable Identity.
   - Enable Git Gateway (Identity → Services).
   - Invite yourself as a user (Identity tab → Invite user).
   - Visit `yourname.netlify.app/admin` → accept invite → log in → edit content → publish (auto-commits to GitHub, redeploys site).
