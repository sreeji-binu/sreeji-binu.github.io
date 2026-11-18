# My Personal Portfolio

A single-page personal portfolio website for Sreeji Rajendran, covering virtual assistance, administration, web and graphic design, social media, data analytics and AI video creation. It includes a services section and a quote request form for clients in Oman and worldwide.

## Features

- Responsive layout that works on phones, tablets and desktops
- Sections: Home, About, Roles, Skills, Sample projects, Services, Courses, Contact
- Services and packages: seven services, each with Essential, Standard and Custom levels
- Custom quotation pricing, with a "how it works" process
- "Request a free quote" form (name, email, country, service, project description, deadline, optional budget)
- Mobile navigation menu and smooth scrolling

## Built with

- HTML
- CSS
- JavaScript

No frameworks, libraries or build tools. The whole site is one file: `index.html`.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any web browser.

## Deploy with GitHub Pages

1. Push `index.html` to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

## Customise

- **Contact details:** update the name, phone, email and LinkedIn link in the Contact section.
- **Quote form email:** change `QUOTE_EMAIL` in the script at the bottom of `index.html`.
- **Services:** edit the `<details class="svc">` blocks in the Services section, and keep the service options in the form's dropdown in sync.
- **Colours:** change the CSS variables at the top of the `<style>` block (`--navy`, `--blue`, and so on).
- **Projects:** add screenshots and links to each sample project as they are ready.

## How the quote form works

The form has no backend. When a visitor submits it, their email app opens with the request filled in and addressed to `QUOTE_EMAIL`, and a "Copy message" button is shown as a fallback. To receive requests directly in your inbox, connect a form service such as Formspree or Netlify Forms.

## Notes

- Sample projects are labelled as portfolio work or practice concepts, not paid client work.
- Courses are listed as learning completed, not as professional certifications, unless the provider issued a certification.
- Finance support is limited to documentation and record-keeping. It is not statutory audit, tax certification or regulated professional advice.

## Contact

Sreeji Rajendran, Muscat, Oman
Email: sreejibinu1995@gmail.com
LinkedIn: https://linkedin.com/in/sreeji-binu-44067a3a8

## License

© 2026 Sreeji Rajendran. All rights reserved.
