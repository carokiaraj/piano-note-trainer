# Piano Note Trainer

A static, client-side piano learning app. No build step or backend required.

## Deploy to Vercel

### Via GitHub (recommended)
1. Create a new GitHub repository (for example, `piano-note-trainer`).
2. Upload `index.html` and `vercel.json` from this folder to the repository root.
3. In Vercel, choose **Add New > Project**, import the repository, and deploy.
4. Framework Preset: **Other**; Build Command: leave empty; Output Directory: leave empty (project root).
5. Vercel provides a public `*.vercel.app` URL after deployment.

### Via Vercel CLI
From this folder, run:

```bash
npx vercel login
npx vercel --prod
```

Accept the prompts to link or create a Vercel project. The command prints the public deployment URL.

## Notes
- Quiz history is stored in each visitor's browser, not in a shared database.
- No server-side API keys or secrets are needed.
- To update, edit `index.html` and redeploy.
