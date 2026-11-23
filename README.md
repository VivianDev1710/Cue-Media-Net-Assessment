# cue. prototype — static build

`index.html` is the complete Cue prototype in a single self-contained file (app code, styles, logo and today's news content are all inside it). No build step, no dependencies.

## Host on Vercel via GitHub
1. Create a new GitHub repository.
2. **Add file → Upload files**, select both files in this folder (`index.html`, `README.md`), commit.
3. In Vercel: **Add New → Project → Import** the repository.
   - Framework Preset: **Other**
   - Build Command: leave empty · Output Directory: leave empty (root)
4. Deploy. The prototype is served at the project URL.

Demo controls: press **Shift + D** (or add `?demo=1` to the URL).
