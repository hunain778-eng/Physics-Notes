PHYSICS NOTES WEBSITE (GitHub Pages) - one-time setup
1. Sign in at github.com -> New repository. Name it e.g. physics-notes. Choose PUBLIC. Create.
2. In the repo: Add file -> Upload files. Drag in everything from this folder (index.html, logo.jpg, ClassIX, ClassXI, README). Commit.
3. Add the auto-update file: Add file -> Create new file. Type the name:  .github/workflows/update-notes.yml
   Paste the contents of update-notes.yml (included in this folder) and Commit.
4. Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder /(root) -> Save.
5. Settings -> Actions -> General -> Workflow permissions -> "Read and write permissions" -> Save.
6. After a minute your site is at:  https://YOUR-USERNAME.github.io/physics-notes/   (share this link; no sign-in needed).

ADDING NOTES LATER: open the repo, go into the folder ClassIX or ClassXI, Add file -> Upload files, choose the PDF/PPT, Commit.
The list updates by itself in about a minute. The file name becomes the title (e.g. "Ch3 Dynamics.pdf").
To delete a note: open the file in the repo -> trash icon -> Commit.
To change the logo: upload a new image named logo.jpg to the repo root (replace the old one).
