OctoFit Tracker — Frontend scaffold notes

Planned frontend: React (Create React App / Vite) with a small component library.

Suggested steps
1. From repository root, create a frontend folder (if not present):
   - `mkdir -p octofit-tracker/frontend`
2. Use a tool to scaffold a React app, for example with Vite:

```bash
# using npm + Vite (recommended for modern apps)
cd octofit-tracker/frontend
npm create vite@latest . --template react
npm install
```

3. Start the dev server:

```bash
npm run dev
```

Notes
- We'll wire authentication and API calls to the backend later.
- Keep the frontend and backend in separate folders as in the repository structure.
