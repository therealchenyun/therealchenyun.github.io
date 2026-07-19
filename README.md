# therealchenyun.github.io

Personal academic homepage of Chen Yun (Ruby), VIC Lab, KAIST.

## Deploy on GitHub Pages
1. Create a **public** repo named exactly `therealchenyun.github.io` under your account.
2. Push these files to the `main` branch:
   ```bash
   git init && git add . && git commit -m "initial homepage"
   git branch -M main
   git remote add origin https://github.com/therealchenyun/therealchenyun.github.io.git
   git push -u origin main
   ```
3. The site goes live at https://therealchenyun.github.io/ within a few minutes
   (Settings → Pages → Source: `main` branch, if not enabled automatically).

To update the CV later, just replace `Chen_Yun_CV.pdf` and push.
