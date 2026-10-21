# Debene Monday — Custom Portfolio

A responsive static portfolio using HTML, CSS, and JavaScript. Theme: dark blue and purple. Hero identity: DM initials logo.

## 1. Preview locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Firefox, or another browser.
3. Edit the files with Visual Studio Code or another text editor.

## 2. Add your downloadable CV
The CV button points to `assets/Debene-Monday-CV.pdf`.
- Export your CV as a PDF.
- Name it exactly `Debene-Monday-CV.pdf`.
- Put it in the `assets` folder, next to `favicon.svg`.
- The included CV placeholder is a text file named `CV-PLACEHOLDER.txt`; remove it after adding your real PDF. Do not publish a placeholder as if it were your CV.

## 3. Add project screenshots
1. Put six screenshots in `assets/screenshots/`.
2. Name them `project-1.jpg`, `project-2.jpg`, ... `project-6.jpg` (or update the corresponding paths and file extensions in `index.html`).
3. Use your own project screenshots, with no private user data or secret keys visible.
4. Refresh the page to see them. The screenshot cards are permanent image paths, so screenshots work on the live website too.

## 4. Personalize your details
Open `index.html` and replace:
- `your-email@example.com` with your public professional email.
- `your-username` in the GitHub and LinkedIn URLs with your real usernames.
- Project summaries with accurate details, and add real repository or live demo links where appropriate.
- Update skills to reflect the tools you can confidently use.

Search for `your-` in `index.html` to find sample contact details.

## 5. Publish to GitHub Pages (free)
1. Sign in to GitHub and create a new public repository, for example `debene-monday-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, `README.md`, and the `assets` folder. Keep the folder structure intact.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for the Pages deployment to finish. The site URL is typically `https://YOUR-USERNAME.github.io/debene-monday-portfolio/` (replace `YOUR-USERNAME` with your GitHub username). GitHub shows the exact URL in Settings → Pages.

## 6. Connect a custom domain (optional)
You can use a domain you own, such as `debenemonday.dev` or another available domain:
1. Register the domain with a domain registrar.
2. In GitHub repository **Settings → Pages → Custom domain**, enter your domain and save.
3. Follow GitHub's current DNS instructions for your chosen domain type at https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site .
4. Wait for DNS and HTTPS setup to complete. Do not change DNS records randomly; use the values GitHub displays in its documentation.
A custom domain costs money and availability depends on the domain name. GitHub Pages hosting for a static portfolio is free.

## Notes
- This is a static portfolio. It does not include a server, database, login system, or contact-form backend.
- Google Fonts are loaded from the web; the rest of the site is plain static HTML/CSS/JS.
- Make sure all image and CV paths are uploaded with the correct letter case. GitHub Pages is case-sensitive.
