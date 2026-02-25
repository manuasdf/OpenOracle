# OpenOracle 🔮

A minimal decision-making tool that helps you choose between two options using cryptographically secure randomness.

## Features

- ✅ **Zero dependencies** - Single HTML file
- ✅ **Cryptographically secure** - Uses `crypto.getRandomValues()`
- ✅ **Works everywhere** - Runs in any modern browser
- ✅ **Static website** - Can be hosted on GitHub Pages, Netlify, or any static host
- ✅ **Mobile friendly** - Responsive design

## How to Use

1. **Enter two options** in the input fields
2. **Click "Ask the Oracle"** button
3. **Get your answer** instantly!

## Try it Live

👉 [Try OpenOracle now](https://manuasdf.github.io/OpenOracle/)

Or download and open `index.html` in any browser - no installation required!

## Technical Details

- **Randomness Source**: `window.crypto.getRandomValues()` - the most secure random number generator available in browsers
- **Algorithm**: 50/50 chance between two options
- **No Tracking**: Zero analytics, cookies, or external requests
- **Offline First**: Works without internet connection

## Development

This is a single-file application. No build step required!

```bash
# That's it! No npm, no webpack, no dependencies.
```

## License

MIT - Use it freely for personal or commercial purposes.

## Contributing

Pull requests welcome! Keep it simple and minimal.

---

Made with ❤️ for indecisive people everywhere.