#  Bike — Landing Page

A responsive landing page for a modern electric bike brand, built as a front-end layout practice project. The page presents the bike lineup, key features, and a contact section with a clean, image-driven design.

** [Live Demo](https://limerider.github.io/MyBikeLandinng/)**

##  Overview

The landing page is built around a single-page structure with smooth in-page navigation and includes:

- **Hero section** — "Take the Streets" headline with a call-to-action to book a test ride
- **Compare Bikes** — a showcase of three bike models with pricing and short descriptions
- **The Details** — feature highlights (auto-unlock, battery range, integrated lights, hydraulic disc brakes) paired with responsive imagery
- **Contact section** — a contact form alongside phone, email, and address details with a Google Maps link
- **Responsive navigation** — a collapsible mobile menu

##  Built With

- **HTML5** — semantic markup
- **SCSS** — modular partials (`_header`, `_about`, `_product`, `_compare`, `_details`, `_contact`, `_footer`, etc.) compiled to CSS
- **JavaScript** — interactive behavior (mobile menu, etc.)
- **Parcel** — zero-config module bundler for building and serving the project
- **ESLint, Stylelint, LintHTML** — code quality and style consistency
- **gh-pages** — deployment to GitHub Pages

##  Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm

### Installation

```bash
git clone https://github.com/LimeRider/MyBikeLandinng.git
cd MyBikeLandinng
npm install
```

### Available Scripts

| Command | Description |
|---|---|
| `npm start` | Runs the project locally in development mode |
| `npm run build` | Builds the production-ready bundle |
| `npm run lint` | Lints HTML, SCSS, and JavaScript |
| `npm run deploy` | Builds and publishes the project to GitHub Pages |
| `npm test` | Runs linting followed by tests |


##  Deployment

The project is deployed via GitHub Pages using `gh-pages`, configured through the `homepage` field in `package.json`:

```bash
npm run deploy
```

## License

This project is licensed under the GPL-3.0 License — see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- Built as part of the [Mate Academy](https://mate.academy/) front-end curriculum, based on the `gulp-boilerplate` template.

