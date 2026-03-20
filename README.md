# River Raid Website

A clone of [River Raid](http://www.worldofspectrum.org/infoseekid.cgi?id=0004154), a classic [ZX Spectrum](http://en.wikipedia.org/wiki/ZX_Spectrum) 48K game published by [Activision](https://en.wikipedia.org/wiki/Activision), compiled to WebAssembly and playable in the browser.

## About

This repository hosts the website for [river-raid-ebiten](https://github.com/river-raid/river-raid-ebiten), a River Raid clone built with the [Ebitengine](https://ebitengine.org/) game library in Go. The game is compiled to WebAssembly (WASM) and runs directly in the browser.

## How to Play

Visit the hosted version, or run a local HTTP server (required — opening `index.html` directly via `file://` will fail due to browser CORS restrictions):

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.
