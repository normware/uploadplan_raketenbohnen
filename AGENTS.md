# Agents

## Commands

- Serve locally: `python3 -m http.server 8000` in project root
- Open in browser: `open http://localhost:8000`

## Project Structure

- `index.html` – main schedule page
- `css/` – ASTA design system CSS
- `js/` – ASTA design system JavaScript
- `fonts/` – JetBrains Mono web fonts
- `README.md` – documentation
- `AGENTS.md` – this file
- `LICENSE` – MIT license

## Conventions

- Keep monospace grid layout using ASTA's design tokens
- Use ASTA theme system (`data-theme`, `.theme-toggle`) for dark/light mode
- Box-drawing aesthetic is achieved via CSS borders on tables, not unicode chars
- All user-facing text in German
- Fetch data from `api.rocketbeans.tv` endpoints
