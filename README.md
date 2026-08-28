# Tegar Maulana — Portfolio Website

Static multi-page portfolio for Tegar Maulana, Information Systems student at Mercu Buana University Meruya.

## Pages
- `index.html` — Home
- `projects.html` — All projects
- `about.html` — About / education / programming languages
- `contact.html` — Contact information and contact form demo
- `project-discord-store.html` — Discord Auto Store case study
- `project-klug.html` — KLUG website case study
- `project-java-store.html` — Java Web Store case study
- `project-generative-ai.html` — Generative AI project
- `project-lua.html` — Lua Automation & Scripting + GitHub repository link

## Project assets
- `assets/discord-store.webp`
- `assets/klug-website.png`
- `assets/java-store.png`
- `assets/profile-photo.svg` — temporary portrait placeholder

## Logo / icon assets
All replaceable icons are stored in:

`assets/icons/`

Current filenames:
- `lua.svg`
- `java.svg`
- `python.svg`
- `javascript.svg`
- `html.svg`
- `css.svg`
- `php.svg`
- `database.svg`
- `github.svg`
- `linkedin.svg`
- `instagram.svg`
- `whatsapp.svg`
- `email.svg`
- `discord.svg`

### Easiest way to replace a logo
Find the logo you want, export/download it as SVG, and overwrite the matching file while keeping the same filename.

Example:
1. Download your preferred official Python SVG.
2. Rename it to `python.svg`.
3. Replace `assets/icons/python.svg`.
4. Refresh the website. No HTML editing is needed.

If you use PNG instead of SVG, change the related HTML `src` from `.svg` to `.png`.

## Social/contact links already added
- Email: `66tegar66@gmail.com`
- WhatsApp: `089629979838`
- GitHub: `https://github.com/66tegar66-svg`
- LinkedIn: `https://www.linkedin.com/in/tegar-maulana-58703a335/`
- Instagram: `https://www.instagram.com/sva_tegar/`

## Lua repository
The portfolio Lua project now links to:

`https://github.com/66tegar66-svg/lua-script`

Visitors can open the Lua project case-study page and then open the source code on GitHub.

## CV / Resume
- `assets/Tegar-Maulana-CV.pdf` — CV shown from the **CV** button in the top-right navigation.
- Keep this filename if you replace the CV later, so you do not need to edit every HTML page.

## Run locally
No build step is required.

Option 1: double-click `index.html`.

Option 2:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Deploy with GitHub Pages
1. Create/open your portfolio repository.
2. Upload all files and folders from `tegar-portfolio`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose branch `main` and `/ (root)`.
6. Save.
