# OBHS Club Hub

Old Bridge High School — Student Life club flyer generator and directory.

## Features
- **Flyer Generator** — live preview, print-to-PDF at 5.5×8.5"
- **Club Directory** — searchable, filterable listing of all approved clubs
- **Submit a Club** — club presidents submit info for Student Life approval
- **Student Life Admin** — review pending submissions, approve/reject, print any flyer

## Deploy to Vercel (5 minutes)

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import that repo
3. Framework: Create React App (auto-detected)
4. Click Deploy — done. You'll get a URL like `obhs-clubs.vercel.app`

## Local development

```bash
npm install
npm start
```

## Customization

- School colors and fonts: edit the `C` token object at the top of `src/App.jsx`
- Seed clubs: edit the `SEED_CLUBS` array
- Add a real backend: swap the in-memory `clubs` state for a fetch to your Google Apps Script endpoint

## Notes

The admin tab is accessible to anyone with the URL. For a real deployment,
consider protecting it with a simple password or linking it to a Google account.
