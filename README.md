# StockAsset India Pro — 3D Wealth & FIRE Simulator

An interactive wealth compounding and equity simulator tailored for the Indian financial market, modeling CAGR, FIRE targets, and post-tax returns.

## Features

- Interactive investment compound calculator modeling SIP (Systematic Investment Plan) and lumpsum investments
- Indian financial market presets (NIFTY 50, Sensex, Midcap, Debt, Gold) with realistic historical CAGR returns
- Advanced FIRE (Financial Independence, Retire Early) planning calculator predicting years to financial freedom
- Indian taxation modeling accounting for Long-Term Capital Gains (LTCG) and Short-Term Capital Gains (STCG)
- Interactive wealth growth charts visualizing corpus appreciation over 5 to 40 year horizons
- Optional integration for live stock quotes via market APIs (e.g. Finnhub)

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Tailwind CSS
- Font Awesome
- Chart.js
- LocalStorage API

## Screenshots

<!-- TODO: Add application screenshots here -->
![StockAsset India Pro — 3D Wealth & FIRE Simulator Screenshot](https://via.placeholder.com/800x450.png?text=StockAsset+India+Pro+—+3D+Wealth+and+FIRE+Simulator)

## Folder Structure

```
StockAsset-Calculator/
├── stockasset_india_pro.html
└── README.md
```

## Installation & Setup

This is a standalone, client-side web application. No complex build pipelines, database configurations, or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SSManikandaprabu/StockAsset-Calculator.git
   cd StockAsset-Calculator
   ```

2. **Run the application:**
   - **Direct Browser Launch**: Double-click `stockasset_india_pro.html` to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   - **Or via Local HTTP Server**:
     ```bash
     python -m http.server 8000
     ```
     Then open [http://localhost:8000/stockasset_india_pro.html](http://localhost:8000/stockasset_india_pro.html) in your browser.

## Usage

1. Launch the application in your browser following the setup instructions above.
2. Interact with the application controls and input fields tailored for StockAsset India Pro — 3D Wealth & FIRE Simulator.
3. Preferences and data are stored locally in your browser's LocalStorage where applicable.

## Environment Variables

FINNHUB_API_KEY: Optional for live real-time market data quotes.

## Live Demo Link

<!-- TODO: Add live demo link once deployed (e.g. GitHub Pages or Vercel) -->
_No live demo link currently configured. Refer to the TODO section below._

## Project Roadmap & TODOs

- [ ] Add screenshot of the compounding growth projection chart and FIRE timeline

## Author

- **S.S. Manikanda Prabu** - [GitHub Profile](https://github.com/SSManikandaprabu)
