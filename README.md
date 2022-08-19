# SolidJS Chrome Extension boilerplate

An easy way to create Chrome extensions with SolidJS using Vite + CRXJS.

# Features

For more functionality, check out [CRXJS](https://github.com/crxjs/chrome-extension-tools) they do all the heavy lifting.

# Installation

1. Clone this repo
2. Install dependencies `pnpm install`
3. Run with `pnpm dev` for HMR or `pnpm build` to build
4. Load your extension in Chrome
   1. Go to `chrome://extensions`
   2. Enable `Developer mode`
   3. `Load unpacked extension`
   4. Select the `/dist` folder 

# Structure

Define your extension entry points in `manifest.config.ts` for Manifest V3 configuration options check out the [chrome docs](https://developer.chrome.com/docs/extensions/mv3/intro/)