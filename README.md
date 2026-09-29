# Taco-shop-Lerning

> A small multi-page HTML/CSS website built as a learning exercise.

A four-page static website for a fictional taco shop, built as a practice
project for learning basic HTML structure and CSS layout.

## Features

- **Four pages** — Home (with menu), Hours, Contact, and About.
- **Responsive layout** — flexbox/grid-based structure that adapts to viewport width.
- **Menu section** — a `#menu` anchor on the home page listing items and prices.
- **Contact page** — address, hours, and a clickable `tel:` phone link.
- **Image assets** — locally stored food photography in `img/`.
- **Zero dependencies** — no JavaScript, no framework, no build step.

## Tech Stack

- **HTML5** — four pages in the repository root.
- **CSS3** — one stylesheet, `css/style.css`.
- **Static images** — `img/`, plus `favicon.ico`.

No JavaScript is used anywhere on this site.

## Installation

There is nothing to install:

```bash
git clone https://github.com/Hashim-Zj/Taco-shop-Lerning.git
cd Taco-shop-Lerning
```

## Usage

Open `index.html` in any browser, or serve it locally:

```bash
python3 -m http.server 8000
# -> http://localhost:8000
```

The site is also published at
<https://hashim-zj.github.io/Taco-shop-Lerning/>.

## Project Structure

```text
Taco-shop-Lerning/
├── index.html      Home page, includes the #menu section
├── about.html      About the shop
├── contact.html    Address, hours, phone
├── hours.html      Opening hours
├── css/
│   └── style.css   Stylesheet for all pages
├── img/            Food photography
└── favicon.ico
```

## Configuration

None. The site takes no configuration, environment variables, or build input.

## Development

There is no build step and no test suite. Edit any `.html` file or
`css/style.css` and reload the browser.

All internal links are **relative** (`index.html`, `about.html`,
`index.html#menu`) rather than root-absolute (`/`, `/#menu`), so the site works
correctly when served from a subdirectory such as a GitHub Pages project path.

## License

No license file is present. Add one before redistributing this code.
