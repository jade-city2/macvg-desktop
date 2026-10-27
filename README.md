# MacVG Desktop
Basic MacVG client. Largely vibe-coded, but input from me too.
## this is just an iframe so far, don't expect much
# Devlopment
Clone this repo:
```bash
git clone "https://github.com/jade-city2/macvg-windows"
cd macvg-windows 
npm install # installs Electron and dependencies
npm start # starts the app
```
To build the Windows installer:
```bash
npm run dist:win # normal setup
npm run dist:portable # portable version
```
To build a Linux AppImage:
```bash
npm run dist:linux
```

To build a macOS DMG:
```bash
npm run dist:mac
```
Note: macOS builds must be run on a Mac (or via CI on macOS). Place an `icon.icns` in a `build/` folder for a custom app icon.

To build for all platforms at once:
```bash
npm run dist:all
```