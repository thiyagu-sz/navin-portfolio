# Repository Guidelines

## Project Structure & Module Organization
The project is a lightweight, single-page portfolio website.
- **index.html**: The core file containing the entire structure, embedded Tailwind CSS configuration, custom styles, and portfolio content.
- **profiles/**: Directory containing original image assets (`.HEIC`, `.jpeg`) for the portfolio owner.

## Build, Test, and Development Commands
This project does not currently use a build system, package manager, or automated testing framework.
- **Development**: Open `index.html` directly in a browser.
- **Styling**: Tailwind CSS is integrated via CDN. Custom theme extensions are defined in the `<script id="tailwind-config">` block within `index.html`.

## Coding Style & Naming Conventions
- **HTML**: Maintain semantic structure within `index.html`.
- **CSS**: Use Tailwind CSS utility classes for layout and design. Custom CSS should be added to the `<style>` block in the `<head>`.
- **Assets**: New profile images should be placed in the `profiles/` directory.

## Commit & Pull Request Guidelines
- Use descriptive commit messages (e.g., "Initial commit").
- Direct commits to the `main` branch are acceptable for small updates, but feature branches are recommended for significant layout or content changes.
