## Basic React Boilerplate

### Usage

1. Clone this repo
2. Navigate to the root and `npm install`
3. Start Webpack: `npm run webpack`
4. Open up `index.html` in your browser to see the `<App>` component rendered!

### Why not just use `create-react-app`?

`create-react-app` is a great way to quickly scaffold a React app, but you'd need to eject to uncover all the configuration under the hood.

This (very) basic boilerplate exposes `webpack.config.js` and assigns `module.exports` to the Webpack config object. In particular:

- Entry and output files are set (i.e., `entry.jsx` and `bundle.js`, respectively)
- Babel is configured to transpile React and ES6 syntax
- `devtool` leverages Source Maps to get access to original source code during debugging
- Both `.js` and `.jsx` files are resolved
