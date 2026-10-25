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
npm run dist # normal setup
npm run dist:portable # portable version
```
To build a Linux AppImage:
```bash
npm run dist:linux
```
Builds appear in the `release` folder.