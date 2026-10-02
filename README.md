# DCAC Voicebox

Anonymous complaint & suggestion box for the **Delhi College of Arts & Commerce
Student Council**. Static frontend in `public/`, three serverless API routes
in `api/`, shared auth helper in `lib/`, and data stored in Upstash Redis.

- **Submit** a complaint or suggestion in seconds — no login, no name.
- **Track** any submission with a short code like `DCAC-7F3K2Q`.
- **Know Your Council** — the elected office bearers for 2026–27.
- **Council desk** — password-protected board for the Council team to triage,
  reply, and resolve.

---

## Deploy in under 10 minutes

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "dcac-voicebox"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main