# Personal Portfolio Website

A static personal portfolio built with HTML5 and CSS3. It organizes background information, technical skills, selected projects, GitHub statistics, and contact links into a single-page layout.

## Overview

The page contains six sections:

- **Home:** Profile image, short introduction, and navigation to projects and GitHub.
- **About:** Background and interests in software, electronics, and related fields.
- **Skills:** Programming languages, development tools, and platforms, displayed with external icon assets.
- **Projects:** Cards describing a smart greenhouse, a local voice assistant, and this portfolio website.
- **GitHub:** Embedded contribution statistics and language summaries.
- **Contact:** Links to GitHub and email.

Navigation uses in-page anchors. The interface uses a dark color palette, blue accents, CSS gradients, hover transitions, and responsive layouts for smaller screens.

## Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Document structure and content |
| CSS3 | Layout, typography, visual effects, and responsive behavior |
| [Skill Icons](https://skillicons.dev/) | Technology and platform icons |
| [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) | GitHub statistics and language cards |

No JavaScript framework, package manager, or build process is required.

## Project Structure

```text
.
├── Portfolio Website.html          # Main HTML document
├── style.css                       # Styles and responsive breakpoints
├── My picture 2.jpg                # Supplied profile photo (see setup)
├── Modul-Pertemuan-1-HTML-Dasar.md # Introductory HTML learning module
└── README.md                       # Project documentation
```

The HTML currently expects the profile image at `images/profile.jpeg`. The supplied image has a different name and location; update the asset path before running the page.

## Running Locally

1. Clone or download the repository.
2. Keep `Portfolio Website.html` and `style.css` in the same directory.
3. Create an `images/` directory and copy `My picture 2.jpg` into it as `profile.jpeg`, **or** change the image `src` in the HTML to `My picture 2.jpg`.
4. Open `Portfolio Website.html` in a modern browser.

Alternatively, serve the directory with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/Portfolio%20Website.html`.

## Implementation Notes

- The page is organized with semantic elements including `header`, `nav`, `main`, `section`, `article`, and `footer`.
- Section links use IDs such as `#about`, `#skills`, and `#projects`; smooth scrolling is configured in CSS.
- CSS Grid is used for the hero layout, project cards, and contact links. Flexbox is used for navigation and skill items.
- Media queries at `850px` and `600px` adapt the layout for narrower viewports.
- The sticky header uses a translucent background and `backdrop-filter` blur.
- Skill icons and GitHub statistics are loaded from third-party services, so these elements require an internet connection and depend on service availability.

## Additional File

`Modul-Pertemuan-1-HTML-Dasar.md` is a separate introductory HTML lesson in Indonesian. It covers HTML structure, common tags, a basic biodata-page exercise, and follow-up tasks. It is reference material rather than a runtime dependency of the portfolio.

## Customization

Edit `Portfolio Website.html` to update the introduction, skills, project descriptions, navigation, and contact links. Edit `style.css` to adjust colors, spacing, typography, layout, and animations.

The current GitHub links and statistics are configured for [`FlameCode1`](https://github.com/FlameCode1). Update those URLs and the statistics image parameters if reusing the template for another profile.
