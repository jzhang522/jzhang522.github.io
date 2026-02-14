# Portfolio Landing Page

A modern, information-dense portfolio website showcasing projects, skills, education, and experience. Built with Vite, Tailwind CSS, and Sass.

## Project Overview

This portfolio website presents a comprehensive view of professional work, technical skills, and background. The site features:

- **Hero sections** with visual highlights for different content areas
- **Project showcase** with expandable project cards and detailed descriptions
- **Skills display** with an animated ticker and categorized skill tables
- **Education & Experience** timeline
- **Contact section** with resume download
- **Responsive navigation** with mobile menu support
- **Search functionality** for finding specific content

The site is built as a single-page application with smooth scrolling navigation and interactive components.

## How to Run

### Development

Start the development server with hot module replacement:

```bash
npm run dev
```

The site will be available at `http://localhost:5173` (or the next available port).

### Build

Create a production build:

```bash
npm run build
```

The optimized files will be output to the `dist/` directory.

### Preview

Preview the production build locally:

```bash
npm run preview
```

This serves the built files from the `dist/` directory for testing before deployment.

## Tailwind vs Sass Strategy

- **Separate CSS into Sass partials** — organize styles into modular files (e.g., `_base.scss`, `_layout.scss`, `_components.scss`) and import them in `main.scss`.

- **Convert CSS variables to Sass variables** — replace `--variable-name` with `$variable-name` for easier reuse and computation.

- **Refactor layouts to Tailwind** — replace flexbox, grid, and spacing styles with Tailwind utility classes in HTML while keeping colors and complex styles in Sass.

- **Keep colors and complex styles in Sass** — maintain dynamic values, hover effects, gradients, and other computations in Sass.

- **Extract static, repeated styles into placeholders** — use `%placeholder` + `@extend` to share common styles between multiple classes.

- **Refactor repeated patterns into mixins** — encapsulate similar structures in `@mixin` and reuse them with `@include` to reduce duplication.

## GitHub Repository

[View on GitHub](https://github.com/jzhang522/SSDP-2850-0-A05)
