# ADS Exam Prep

MCQ practice for Algorithms & Data Structures (173 questions).

## Deploy on Vercel

### Option A — separate project (recommended)

1. Push this repo to GitHub.
2. [vercel.com/new](https://vercel.com/new) → Import the repo.
3. Deploy (root is this repo — no subdirectory needed).
4. Vercel serves `index.html` at `/`.

### Option B — CLI

```bash
npx vercel
npx vercel --prod
```

### Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Single-page quiz app (entry point) |
| `vercel.json` | Static deployment config |

## Notes

- No build step — static HTML only.
