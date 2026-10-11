# RASC Edmonton Centre: Website Redesign

A four-page website redesign concept for the **Royal Astronomical Society of Canada (RASC), Edmonton Centre**, designed and hand-coded in HTML and CSS.

Built by **Samir Solanki** as Project 4 for **DESN 340** in the Post Diploma in Digital Design Experience at **MacEwan University** (Fall 2025).

> This is a student concept project. It is not the official RASC Edmonton website.

## Pages

| Page | File | What it shows |
|---|---|---|
| Home | `home.html` | Centre introduction, observing and imaging certificates, Astrospheric forecast, volunteering, upcoming events, and a contact form |
| Events | `event.html` | Monthly event calendar with stargazing sessions and regular meetings |
| Stardust | `stardust.html` | About the Stardust newsletter and a month-by-month archive |
| Loaners | `loaners.html` | Telescope loaner program with availability for each telescope |

## My role

I led the project end to end, from research to a working, coded site:

1. **Research:** reviewed the existing RASC Edmonton content to identify the most important and most-used pages, the key user groups, and their reasons for visiting.
2. **Information architecture:** created a site map to guide navigation and content priorities.
3. **Design:** moved from sketches to wireframes, then to a fully interactive prototype.
4. **Development:** coded all four pages in HTML and CSS.

## Built with

- **HTML5** and **CSS3**, with no frameworks
- **normalize.css** for consistent styling across browsers
- A custom grid in `layout.css` (`row` and `col-lg-*` classes) and the visual design in `style.css`
- **Google Fonts:** Roboto and Space Grotesk

## Accessibility

The site was built with WCAG accessibility guidelines in mind. In October 2026, the original course version received an accessibility update:

- Added descriptive alt text to every image (logo, certificate badges, newsletter covers, calendar, social icons)
- Set the page language with `lang="en"` on every page
- Gave the search box an accessible name
- Linked every contact form label to its field and added `autocomplete` hints for name and email
- Fixed a stray closing tag in the footer and two typos

You can see these changes compared with the original course submission in the commit history.

## Run it locally

No build step is needed. Download or clone the repository and open `home.html` in any browser.

```bash
git clone https://github.com/<your-username>/rasc-edmonton-redesign.git
cd rasc-edmonton-redesign
open home.html
```

## Project structure

```
rasc-edmonton-redesign/
├── index.html        # Redirects to home.html (for GitHub Pages)
├── home.html
├── event.html
├── stardust.html
├── loaners.html
├── normalize.css
├── layout.css        # Grid and layout
├── style.css         # Colours, type, and components
└── Images/
```

## Credits

The RASC name, logo, observing certificate badges, and Stardust newsletter content belong to the Royal Astronomical Society of Canada. Photos belong to their respective owners. They are used here for educational purposes only.
