# WristDesk Pro

A watch inventory and analytics dashboard for buying, selling, and valuing watches. Built for speed and simplicity in high-volume watch dealing environments.

## Features

- **Dashboard** with live KPIs (inventory value, unrealized P&L, realized profit, avg hold time)
- **Inventory Management** - add, delete, mark sold, toggle listing status with full CRUD
- **Chrono24 Price Lookup** - search any brand/model for estimated fair market value with low/high ranges
- **Watch Identifier** - upload a photo to identify a watch and get instant valuation
- **AI Assistant** - natural language commands to manage inventory:
  - "Mark the Daytona sold for $22,000"
  - "What's my total profit this month?"
  - "Delete the IWC Portugieser"
  - "Add a Rolex Submariner bought for $12,500"
  - "Which watch has been sitting longest?"
- **CSV Export** for spreadsheet compatibility
- **Dark/Light Theme** toggle
- **LocalStorage Persistence** - data survives page reloads
- **Global Search** across all views
- **Keyboard Shortcuts** - Cmd+N to add, / to search

## Tech Stack

- Single-file HTML/CSS/JS (zero build step)
- Chart.js for data visualization
- Lucide Icons
- Inter + JetBrains Mono fonts
- LocalStorage for data persistence

## Usage

Open `index.html` in any modern browser, or deploy via GitHub Pages.

## Deploy with GitHub Pages

1. Go to repo Settings > Pages
2. Set source to `main` branch, root directory
3. Your dashboard will be live at `https://<username>.github.io/wristdesk-pro/`

## License

MIT
