# Harimurali S S | Interactive Portfolio

An interactive, single-page portfolio built for a competition. Scroll the hero image and a torn red band rips it open to reveal the rest of the site.

## Sections
- **Hero:** collage image that zooms and tears open as you scroll
- **About me:** who I am and what I build
- **Projects:** numbered list that wipes in on scroll
- **Certificates:** Thinker Hub participation certificates (Useless Projects 3.0, Sonic Pi), click to enlarge
- **Contact:** LinkedIn, Instagram, email, and a message form powered by EmailJS

## Built with
Plain HTML, CSS and JavaScript in one file (`index.html`). No build step or frameworks.
Fonts: Anton and IBM Plex Mono (Google Fonts). Contact form: EmailJS.

## Run it
Open `index.html` in any browser.

## Deploy
- **Netlify:** drag this folder onto Netlify Drop.
- **GitHub Pages:** push to a repo, then Settings > Pages > Deploy from branch > `main` / root.

## Edit the content
Open `index.html` and find the `projects` and `certs` lists near the top of the script section. The images in `assets/` are already embedded in `index.html`, so the site works as one file; the copies in `assets/` are for reference.

## Contact form setup
The form uses EmailJS (service, template and public key are set in the `EMAILJS` constant). The template needs the variables `{{name}}`, `{{email}}` and `{{message}}`. An EmailJS public key is designed to be public, so it is safe in a public repo.

## Links
- LinkedIn: https://www.linkedin.com/in/harimurali-s-s-b6a989429/
- Instagram: https://www.instagram.com/harimurali.s.s/
- Email: astrohari9746@gmail.com
