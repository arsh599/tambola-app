# 🎰 Tambola Game

A quick, mobile-friendly Tambola (Indian Bingo) game app that works on GitHub Pages. Perfect for playing with multiple users!

## Features

✅ **Two Modes:**
- **Caller Mode**: Call numbers 1-90 randomly
- **Player Mode**: Get a random ticket and mark numbers as they're called

✅ **Multi-User**:
- Share the GitHub Pages link with friends
- Each person opens on their device
- One person acts as caller, others mark their tickets

✅ **Mobile Friendly**:
- Fully responsive design
- Works on phones, tablets, and desktops
- Touch-friendly buttons and number cells

✅ **Local Storage**:
- Game state saves automatically
- Resume game after refreshing page
- Each device maintains its own ticket

## How to Play

1. Open the app (one person is the **Caller**, others are **Players**)
2. **Caller** clicks "Call Number" to randomly call a number (1-90)
3. **Players** mark the called numbers on their ticket
4. Numbers are tracked locally - mark them manually or they auto-mark if called

## Setup on GitHub Pages

Your app is already live at: **https://arsh599.github.io/tambola-app**

### To Enable Pages (if needed):
- Go to **Settings** → **Pages**
- Select `main` branch as source
- Wait for deployment (green checkmark)

### Share the Link:
- Send friends: `https://arsh599.github.io/tambola-app`
- They can open it on their phones immediately!

## How It Works

- **Single HTML File**: Entire app is in `index.html` - easy to customize
- **LocalStorage**: Game state saves to browser storage
- **No Backend Needed**: Pure static site, runs 100% on client
- **No Internet Required**: Works offline once loaded

## Customization

Edit `index.html` to:
- Change colors (look for `#667eea`, `#764ba2`)
- Adjust number range (default 1-90 for traditional Tambola)
- Add sound effects or animations
- Change fonts or layout

## Tips

- **For Caller**: Switch to Caller mode to call numbers
- **For Players**: Switch to Player mode to manage your ticket
- **New Game**: Caller clicks "Reset" to start fresh
- **New Ticket**: Players click "New Ticket" for a different ticket
- **Persistent**: Your game state saves automatically - no login needed!

## License

MIT - Feel free to use and modify!

Enjoy your game! 🎉