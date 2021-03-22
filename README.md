# adapter-vercel

> Special thanks to @elianiva for this good job!

Adapter for Svelte apps that creates a Vercel app, using a function for dynamic server rendering.

## Usage

```sh
npm install --save-dev not-adapter-vercel
```

Then in your `svelte.config.js`:

```js
module.exports = {
  ...
	adapter: 'not-adapter-vercel'
};
```

## Folder Build

`.vercel_build_output/`