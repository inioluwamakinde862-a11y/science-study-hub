# Science Study Hub (Static Site)

A simple, colorful study site for **Physics, Biology, and Chemistry** with notes and in‑browser quizzes.
No servers, no database — just HTML/CSS/JS. Your quiz stats save in your browser (localStorage).

## Files
- `index.html` — Home
- `physics.html`, `biology.html`, `chemistry.html` — Subject pages with notes + quizzes
- `style.css` — Styles
- `script.js` — Quiz engine

## How to host for free (2 easy options)

### Option A: Netlify (drag & drop)
1. Go to netlify.com and log in (Google/GitHub works).
2. Drag the **whole folder** onto the “Deploy site” area.
3. You’ll get a link like `https://your-name.netlify.app`. Share it!

### Option B: GitHub Pages
1. Create a new GitHub repo and upload all files.
2. Settings → Pages → From branch → Select `main` and `/ (root)` → Save.
3. Your site will be at `https://your-username.github.io/repo-name`.

## Editing questions
Open each subject HTML and change the `quizData` object (questions, options, answer index, explanation).
Keep the structure the same.

Happy studying!
