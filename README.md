[![semantic-release](https://img.shields.io/badge/semantic-release-e10079.svg?logo=semantic-release)](https://github.com/semantic-release/semantic-release) [![Build Status](https://app.travis-ci.com/stphn/reveal-vite-protected.svg?branch=main)](https://app.travis-ci.com/stphn/reveal-vite-protected)

# Reveal Vite Staticrypt

![Reveal Vite Staticrypt](docs/preview.webp)

Building Html Presentations with [Reveal.js](https://revealjs.com/) and [Vite](https://vitejs.dev/).

I will assume you have some familiarity with Node.js and have it at least version 8.3 installed.

### Usage

To run the app use following scripts:

with yarn
```
yarn install
yarn dev
```

with npm

```
npm install
nmp run dev
```

The presentation will run locally at `http://localhost:3000`. You can edit the [index.html](https://github.com/stphn/reveal-vite-protected/blob/main/index.html) and [main.js](https://github.com/stphn/reveal-vite-protected/blob/main/main.js) to see it auto-reload.

To build the presentation `yarn build` or `npm run build` which creates the `dist` folder.

### Protecting your presentation

[Staticrypt](https://github.com/robinmoisson/staticrypt) uses AES-256 to encrypt your string with your passphrase in your browser (client side) and this is useful if you need to passphrase protect your presentations.

In order to be able to use the `yarn protect` script, make sure to install the Staticrypt CLI: it is available through npm, install with: `npm install -g staticrypt`


### Docs

[Reveal.js](https://revealjs.com/)

[Vite](https://vitejs.dev/)

[Staticrypt](https://github.com/robinmoisson/staticrypt)



