# RBTV Wochenplan

A monospace schedule viewer for [Rocket Beans TV](https://www.rocketbeans.tv/), showing the weekly live stream and upload plan in a terminal-inspired grid layout.

[GitHub](https://github.com/normware/uploadplan_raketenbohnen) · [Impressum](https://normware.org/impressum.html) · [Datenschutz](https://normware.org/datenschutz.html)

## Features

- Weekly overview of live streams and uploads
- Filter by alle / livestream / upload
- Navigate between weeks (← / →)
- Jump to today's entry with scroll
- Dark/light mode toggle
- Powered by the [ASTA Design System](https://anton.io/asta/)

## Usage

Open `index.html` in a browser or serve locally:

```bash
python3 -m http.server 8000
```

The page fetches data from the RBTV API and renders a monospace grid schedule for the current week.

## Attribution

- **[ASTA Design System](https://anton.io/asta/)** by [Antonio Roldao](https://anton.io) – MIT License
- **[Rocket Beans TV API](https://api.rocketbeans.tv/)** – schedule and publishing data

## License

MIT
