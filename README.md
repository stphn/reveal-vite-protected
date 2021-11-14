[![semantic-release](https://img.shields.io/badge/semantic-release-e10079.svg?logo=semantic-release)](https://github.com/semantic-release/semantic-release)[![Build Status](https://app.travis-ci.com/stphn/reveal-vite-protected.svg?branch=main)](https://app.travis-ci.com/stphn/reveal-vite-protected)

# Reveal Vite Staticrypt

Building Html Presentations with [Reveal.js](https://revealjs.com/) and [Vite](https://vitejs.dev/).

I will assume you have some familiarity with Node.js and have it at least version 8.3 installed.

### Usage
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

see the vite [Vite Documentation](https://vitejs.dev/) for more infos on script.

### Protecting your presentation

[Staticrypt](https://github.com/robinmoisson/staticrypt) uses AES-256 to encrypt your string with your passphrase in your browser (client side) and this is useful if you need to passphrase protect your presentations.

In order to be able to use the `yarn protect` script, make sure to install the Staticrypt CLI: it is available through npm, install with: `npm install -g staticrypt`


### Docs

[Reveal.js](https://revealjs.com/)
[Vite](https://vitejs.dev/)
[Staticrypt](https://github.com/robinmoisson/staticrypt)



