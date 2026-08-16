NATHAN MUSIC GROUP — COMPLETE WEBSITE PACKAGE

This is the visually designed public website package, not a text/README page.

Root files:
- index.html
- CNAME
- assets/nmg-logo.jpg
- assets/nmg.jpg
- assets/nina.jpg
- admin/index.html (portal interface design)

Public website:
- Nathan Music Group branding (NOT Nathan Music World)
- NMG + Nina supplied photos
- Nathan Wunna profile
- Carmén profile
- Releases section
- About section
- Collaborator portal callout
- Responsive mobile/desktop design

SECURE COLLABORATOR PORTAL:
GitHub Pages alone cannot securely authenticate collaborators or provide a private database. The included admin page is the finished UI direction, but it must be connected to an authentication/database service before it is used for real editing.

Recommended production connection:
- Supabase Auth + Postgres + Storage, or an equivalent authenticated backend.
- Approved collaborators only.
- Artist records: name, photo, bio, role, genre, streaming links, social links, releases, cover art, credits and release dates.
- Public site reads published records.
- Collaborators edit records after login.
