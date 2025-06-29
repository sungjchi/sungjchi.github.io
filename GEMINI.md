# GEMINI Project Context: sungjchi.github.io

This file provides context for the Gemini AI assistant to work effectively on this project.

## Project Overview

This is a personal academic website for Sungjae Chi, built with the Jekyll static site generator and the `jekyll-theme-minimalist` theme. It is hosted on GitHub Pages.

## Development

### Prerequisites

Ensure you have Ruby and Bundler installed. Then, install the project dependencies:

```bash
bundle install
```

### Running the Site Locally

To serve the website locally for development, run:

```bash
bundle exec jekyll serve
```

The site will be available at `http://127.0.0.1:4000/`.

## Testing and Validation

### HTML Validation

The project includes a script to validate the generated HTML.

```bash
./script/validate-html
```

### Manual Testing

After making changes, visually inspect the site on both desktop and common mobile screen sizes to ensure layouts are correct.

## Key Files and Conventions

*   **`_config.yml`**: Contains main Jekyll configuration, including site title, description, and color scheme.
*   **`index.md`**: The main content file for the homepage, containing the biography and publications list.
*   **`_layouts/default.html`**: The primary HTML layout file that wraps all pages.
*   **`_sass/jekyll-theme-minimalist.scss`**: The core stylesheet for the theme. Customizations should be added here or in `assets/css/style.scss`.
*   **`assets/img/`**: Directory for images used on the site.
*   **`_includes/`**: Contains HTML snippets that are reused across the site, such as the sidebar and footer.

## Deployment

This is a GitHub Pages site. Changes are automatically deployed when they are pushed to the `main` branch of the `sungjchi/sungjchi.github.io` repository.
