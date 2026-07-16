# amita.exe 💗

A personal, installable love-page with a one-tap SOS button.

## Before you deploy
- Drop your own **`song.mp3`** into this same folder (root, next to `index.html`).
  Any track you own the rights to / royalty-free music works — just name it `song.mp3`.
- Open `index.html` and double check the WhatsApp number near the bottom
  of the `<script>` block (search for `PHONE`) — it's currently set to `919773085739`.

## Deploy on GitHub Pages
1. Create a new repo on GitHub (e.g. `amita-app`), public.
2. Push these files to the `main` branch (see commands below).
3. In the repo: **Settings → Pages → Source → Deploy from branch → `main` / root**.
4. Wait ~1 minute, then your site is live at:
   `https://<your-username>.github.io/<repo-name>/`
5. Open that link on her phone (in Chrome/Safari) — that's the link to send her.
   PWA install + SOS + geolocation only work over HTTPS, which GitHub Pages gives you for free.

## Push with git
```bash
git init
git add .
git commit -m "amita app"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
