# Learn with Fayis website + content manager

Files
- index.html: the website
- content.json: the editable content (demo videos, pictures, links)
- images/: pictures used by the site
- admin/: the content manager (open yoursite.com/admin)

One-time setup (about 15 minutes)
1. Create a free GitHub account and a new repository. Upload all these files to it.
2. Open admin/config.yml and change YOUR-GITHUB-USERNAME/YOUR-REPO-NAME to your repository.
3. Create a free Netlify account, choose "Import from Git" and pick the repository. Deploy.
4. In Netlify: Site configuration > Access & security > OAuth > Install provider > GitHub. Add a GitHub OAuth app when asked (Netlify shows the steps).
5. Open yoursite.com/admin and log in with GitHub.

Everyday use
- Log in at yoursite.com/admin > Website > Videos, pictures and links.
- Change a demo video: paste a new YouTube link. Add a subject with "Add demo lecture videos item".
- Change a picture: click the picture, upload a new one.
- Press Publish. The live site updates in about a minute. No coding.

Notes
- Subject names must be one of the list (Accounts, Auditing, Costing, Corporate Accounts) and match the course.
- If content.json cannot be loaded, the site shows the built-in defaults.
