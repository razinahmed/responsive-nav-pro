# Responsive Nav Pro

![CSS](https://img.shields.io/badge/CSS-Responsive-blue)
![HTML](https://img.shields.io/badge/HTML5-Navigation-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A professional collection of responsive navigation components for web applications. Includes hamburger menus, sidebar drawers, top navigation bars, and bottom tab bars -- all built with pure CSS and progressive enhancement.

## Features

- Multiple navigation patterns (top bar, sidebar, bottom tabs, hamburger)
- Mobile-first responsive design with fluid breakpoints
- Pure CSS toggle for hamburger menu (no JavaScript required)
- Smooth open/close transitions and animations
- Dark theme with customizable accent colors
- Accessible markup with ARIA attributes

## Tech Stack

| Technology | Purpose                |
|------------|------------------------|
| CSS3       | Layout and animations  |
| HTML5      | Semantic navigation    |
| Make       | Build automation       |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/responsive-nav-pro.git
cd responsive-nav-pro
```

2. Include the stylesheet:

```html
<link rel="stylesheet" href="styles/theme.css" />
```

3. Use a navigation component:

```html
<nav class="responsive-nav" role="navigation">
  <a href="/" class="nav-brand">Brand</a>
  <ul class="nav-links">
    <li><a href="/about">About</a></li>
    <li><a href="/contact">Contact</a></li>
  </ul>
</nav>
```

## Theme Variables

| Variable       | Value     | Description       |
|----------------|-----------|-------------------|
| `--primary`    | `#00d4aa` | Link accent color |
| `--background` | `#1e1e2e` | Nav background    |

## Build

```bash
make build
make test
```

## Project Structure

```
responsive-nav-pro/
  styles/
    theme.css       # Navigation styles
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. Please test navigation components across screen sizes and ensure keyboard accessibility.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
