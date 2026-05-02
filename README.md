# CryptoLiqMap - Real-time Cryptocurrency Liquidation Map

🚀 **Live Site: https://mymdo.github.io/CryptoLiqMap/**

A professional, pure HTML/CSS/JS cryptocurrency liquidation map that visualizes real-time liquidations across major exchanges (Binance, Bybit, OKX) using public WebSocket APIs.

## Features

✅ **Zero Dependencies** - Pure HTML, CSS, and JavaScript (no build tools needed)
✅ **Real-time WebSocket Data** - Direct browser connections to exchange WebSockets
✅ **Live Liquidation Feed** - Real-time event stream with filtering
✅ **Interactive Heatmap** - Canvas-based visualization of liquidation clusters
✅ **Statistics Dashboard** - 24h totals, Long/Short ratios, largest liquidations
✅ **Dark/Light Theme** - Toggle with persistent localStorage
✅ **Responsive Design** - Works on desktop, tablet, and mobile
✅ **Free Public APIs** - No API keys required

## Supported Exchanges

- **Binance** - wss://fstream.binance.com/ws/!forceOrder@arr
- **Bybit** - wss://stream.bybit.com/v5/public/linear
- **OKX** - wss://ws.okx.com:8443/ws/v5/public

## Technologies Used

- Pure HTML5
- Pure CSS3 (with CSS Variables for theming)
- Pure JavaScript (ES6+)
- Canvas 2D API for heatmap rendering
- WebSocket API for real-time data

## How It Works

1. **Browser connects directly** to exchange WebSockets (no backend needed)
2. **Liquidations stream in real-time** from 3 major exchanges
3. **Canvas heatmap** visualizes liquidation clusters by price level
4. **Live feed** shows individual liquidation events with details
5. **Statistics update dynamically** as data flows in

## GitHub Pages Deployment

This project is designed for GitHub Pages:
- No build step required
- Just push `index.html` to the `main` branch
- GitHub Pages serves it automatically
- No npm, no node_modules, no dependencies

## Local Development

Simply open `index.html` in a browser:
```bash
open index.html
# or
python3 -m http.server 8000  # then visit http://localhost:8000
```

## Project Structure

```
CryptoLiqMap/
├── index.html          # Complete application (HTML + CSS + JS)
├── README.md          # This file
├── LICENSE            # MIT License
└── .gitignore        # Git ignore file
```

## Contributing

Contributions welcome! Feel free to:
- Add more exchanges
- Improve heatmap visualization
- Add sound notifications
- Enhance statistics and analytics

## Disclaimer

This tool is for informational purposes only. Not financial advice. Use at your own risk.

---

**Built with ❤️ using open public WebSocket APIs**
