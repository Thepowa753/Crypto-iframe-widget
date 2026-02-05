# BTC-iframe-widget

Get data from API and show them in a pretty format. This widget is useful if you have a custom home page like CaretTab or want to embed cryptocurrency prices in an iframe.

## Features

- Real-time cryptocurrency prices from Binance API
- Support for 15+ popular cryptocurrencies
- Multiple fiat currency options
- Light and dark theme support
- Customizable dimensions
- Cryptocurrency-specific color schemes
- Auto-updating prices (every 30 seconds)

## Usage

Embed the widget using an iframe with URL parameters to customize its appearance:

```html
<iframe src="https://thepowa753.github.io/BTC-iframe-widget/?crypto=BTC&fiat=USD&theme=light&width=300&height=200" width="300" height="200" frameborder="0"></iframe>
```

### URL Parameters

| Parameter | Description | Default | Options |
|-----------|-------------|---------|---------|
| `crypto` | Cryptocurrency to display | `BTC` | `BTC`, `ETH`, `BNB`, `XRP`, `ADA`, `DOGE`, `SOL`, `DOT`, `MATIC`, `LTC`, `AVAX`, `LINK`, `UNI`, `ATOM`, `XLM` |
| `fiat` | Fiat currency for price | `EUR` | `EUR`, `USD`, `GBP`, `JPY`, `AUD`, `CAD`, `CHF`, `CNY`, `KRW`, `BRL`, `TRY`, `ZAR` |
| `theme` | Color theme | `light` | `light`, `dark` |
| `width` | Widget width in pixels | `300` | `100` - `2000` |
| `height` | Widget height in pixels | `200` | `100` - `2000` |

### Examples

#### Bitcoin in USD with light theme (default size)
```html
<iframe src="https://thepowa753.github.io/BTC-iframe-widget/?crypto=BTC&fiat=USD" width="300" height="200" frameborder="0"></iframe>
```

#### Ethereum in EUR with dark theme
```html
<iframe src="https://thepowa753.github.io/BTC-iframe-widget/?crypto=ETH&fiat=EUR&theme=dark" width="300" height="200" frameborder="0"></iframe>
```

#### Solana in USD with custom dimensions
```html
<iframe src="https://thepowa753.github.io/BTC-iframe-widget/?crypto=SOL&fiat=USD&theme=light&width=400&height=250" width="400" height="250" frameborder="0"></iframe>
```

#### Dogecoin in GBP with dark theme and large size
```html
<iframe src="https://thepowa753.github.io/BTC-iframe-widget/?crypto=DOGE&fiat=GBP&theme=dark&width=500&height=300" width="500" height="300" frameborder="0"></iframe>
```

## Supported Cryptocurrencies

Each cryptocurrency has its own branded color scheme:

- **BTC** (Bitcoin) - Orange gradient
- **ETH** (Ethereum) - Blue gradient
- **BNB** (Binance Coin) - Yellow gradient
- **XRP** (Ripple) - Dark gray gradient
- **ADA** (Cardano) - Blue gradient
- **DOGE** (Dogecoin) - Gold gradient
- **SOL** (Solana) - Green to purple gradient
- **DOT** (Polkadot) - Pink gradient
- **MATIC** (Polygon) - Purple gradient
- **LTC** (Litecoin) - Blue gradient
- **AVAX** (Avalanche) - Red gradient
- **LINK** (Chainlink) - Blue gradient
- **UNI** (Uniswap) - Pink gradient
- **ATOM** (Cosmos) - Dark gray gradient
- **XLM** (Stellar) - Black gradient

## Themes

### Light Theme
- White background with light colors
- Perfect for light-colored websites
- High contrast for readability

### Dark Theme
- Dark blue background
- Ideal for dark-themed websites or night mode
- Easy on the eyes in low-light conditions

## Technical Details

- Data source: Binance API
- Update frequency: 30 seconds
- Fallback: Mock data when API is unavailable
- No external dependencies
- Pure HTML/CSS/JavaScript

## Development

The widget is a single HTML file with embedded CSS and JavaScript. To modify:

1. Clone the repository
2. Edit `index.html`
3. Test locally by opening in a browser
4. Deploy to GitHub Pages or any web server

## License

This project is open source and available for anyone to use and modify.
